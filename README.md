# Task 8 – Working with VPNs

## Objective
To understand how a Virtual Private Network (VPN) works, how it helps in protecting privacy, and how to verify that the connection is secure.

---

## Tools Used
- ProtonVPN (Free plan)
- Windows 11
- whatismyipaddress.com (for IP check)
- wikipedia.org (for testing connection)

---

## Steps Performed

### Step 1 – Choose and Sign Up
I selected **ProtonVPN**, created a free account from their official website, and verified my email.

### Step 2 – Install the VPN Client
Downloaded the Windows version of ProtonVPN and installed it using default options.

### Step 3 – Connect to a VPN Server
After logging in, I connected to the **Netherlands (NL-FREE#112)** server.  
The app showed **“Protected”** status and displayed a VPN IP address `149.34.244.131`.

### Step 4 – Verify IP Address Change
I opened **whatismyipaddress.com** and confirmed that my location had changed to the Netherlands.  
This proved that the VPN connection was active and traffic was being routed securely.

### Step 5 – Test Browsing
Browsed websites like **Wikipedia** while connected.  
At first, pages loaded a bit slowly (probably due to encryption and routing through a distant server),  
but after a short time the speed was normal and stable.

### Step 6 – Disconnect and Compare
Disconnected the VPN and checked my IP again.  
It reverted to my original Indian IP, confirming that the VPN had successfully hidden my real address while connected.

---

## VPN Encryption and Privacy Features

- **AES-256 encryption** – protects all internet traffic from interception.  
- **OpenVPN and WireGuard** protocols – ensure secure tunneling of data.  
- **IP masking** – hides the real IP address and replaces it with the VPN server’s IP.  
- **No-logs policy** – ProtonVPN does not store user browsing data.  
- **DNS leak protection** – keeps DNS requests private.  
- **Kill switch** – stops all traffic if the VPN connection suddenly drops.

---

## Benefits and Limitations

### Benefits
1. Hides real IP address and location.  
2. Encrypts data and keeps browsing private.  
3. Provides extra protection on public Wi-Fi.  
4. Can access geo-restricted websites.  
5. Prevents ISP tracking and data collection.

### Limitations
1. Slightly slower speed because of encryption.  
2. Free plans have limited servers and bandwidth.  
3. Does not stop malware or phishing attacks.  
4. If the VPN disconnects, data might be briefly exposed.  
5. Not complete anonymity since websites can still track cookies or logins.

---

## Observations
When connected to the Netherlands server, my **IPv4 address changed** from my original Indian IP to the VPN’s IP (`149.34.244.131`).  
This showed that the VPN successfully masked my real identity and encrypted my data.  
Browsing was mostly stable with minor speed changes at the beginning.

---

## Suggested Screenshots
- ProtonVPN app showing “Connected / Protected” status  
- whatismyipaddress.com showing Netherlands IP  
- Optional: Disconnected state showing the original IP

---

## Folder Example
