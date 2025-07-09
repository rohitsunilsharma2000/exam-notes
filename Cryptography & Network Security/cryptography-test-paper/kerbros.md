
---

## ✅ **1. Kerberos Authentication**

### a) Explain the flow of Kerberos authentication protocol.

**📝 ANS : C\&NS-CS-41**

The **Kerberos authentication protocol** uses a ticket-based system to verify user identity securely over untrusted networks.

<img src="https://www.scaler.com/topics/images/kerberos-authentication-2.webp"/>

## How to do Kerberos Authentication Protocols Work? 

<img src="https://www.scaler.com/topics/images/kerberos-authentication-3.webp"/>

**Step-by-step Flow:**

1. **Login Request:**
   The client sends a login request (username) to the **Authentication Server (AS)**.

2. **TGT (Ticket Granting Ticket):**
   If the user is found in the Kerberos database, AS sends back a **TGT** and a **session key**, encrypted with the user's password.

3. **Service Ticket Request:**
   Using the TGT, the client requests a **Service Ticket** from the **Ticket Granting Server (TGS)**.

4. **Service Ticket Response:**
   TGS responds with a ticket encrypted with the **application server’s key**.

5. **Accessing Service:**
   The client sends this service ticket to the **Application Server (SS)**. If valid, access is granted.

🔐 This process ensures **mutual authentication**, and **passwords are never sent** over the network.

---

### b) Describe two common authentication applications other than Kerberos.

**📝 ANS : C\&NS-CS-42**

Here are two widely used authentication systems:

1. **NTLM (New Technology LAN Manager):**

   * Developed by Microsoft for Windows systems.
   * Uses a **challenge-response** mechanism.
   * Less secure than Kerberos; vulnerable to replay and brute-force attacks.

2. **LDAP (Lightweight Directory Access Protocol):**

   * Used to **maintain user information** and perform authentication.
   * Often paired with Kerberos in enterprise environments.
   * Supports **authorization and directory services** in networks.

---

## ✅ **2. Kerberos Model**

### a) Explain the components of the Kerberos model with diagram.

**📝 ANS : C\&NS-CS-43**

The **Kerberos model** includes several components that work together for secure authentication.

**Key Components:**

1. **Client:**
   Initiates service request on behalf of the user.

2. **Authentication Server (AS):**
   Validates the user and issues a **Ticket Granting Ticket (TGT)**.

3. **Ticket Granting Server (TGS):**
   Issues **service-specific tickets** using the TGT.

4. **Service Server (SS):**
   Provides the requested service after verifying the ticket.

5. **Kerberos Database:**
   Stores user credentials and keys.

6. **Key Distribution Center (KDC):**
   A combined server that includes AS, TGS, and the database.

**🔷 Diagram:**

```
Client --> AS --> TGT
Client + TGT --> TGS --> Service Ticket
Client + Service Ticket --> Application Server (SS)
```

🛡️ The model ensures authentication, authorization, and encrypted communication.

---

### b) Discuss client-server authentication using Kerberos.

**📝 ANS : C\&NS-CS-44**

In **client-server authentication using Kerberos**, both the user and the service authenticate each other using tickets.

**Steps:**

1. The client first authenticates to the **Authentication Server (AS)** and gets a **TGT**.
2. Using the TGT, the client requests a **Service Ticket** from the **TGS**.
3. This service ticket is sent to the **Application Server (SS)**.
4. The SS validates the ticket using its secret key.
5. Upon successful validation, **access is granted**.

✅ This process avoids sending passwords over the network and supports **mutual authentication**, which means both client and server confirm each other's identity.

---

