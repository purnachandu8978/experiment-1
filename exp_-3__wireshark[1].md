**EXPERIMENT -3**

**Wireshark**

**Network Packet Capture and Analysis Tool**

**Installation:**

**Windows:** <https://www.wireshark.org/download.html>

**Mac :** <https://www.wireshark.org/download.html>

**Linux:** preinstalled in kali else download source code from same
website

**Procedure:**

**Step 1: Start Capturing Packets**

-   First, open Wireshark. You will see a list of all available network
    interfaces (e.g., \"Wi-Fi,\" \"Ethernet\").

-   Select the interface your computer is using to connect to the
    internet (in this case, Wi-Fi).

-   Click the blue shark fin icon 🦈 in the top-left corner to start the
    capture. Wireshark will immediately begin capturing all traffic
    passing through that interface.


<img width="1920" height="1080" alt="Screenshot (73)" src="https://github.com/user-attachments/assets/1bfb1507-5bed-488a-a7d3-3ad6b56c3834" />

> **Step 2: Generate Login Traffic**

-   Open a web browser and navigate
    to <http://testphp.vulnweb.com/login.php>.

-   Enter any dummy credentials. For this example, we\'ll use:

Username: testuser

Password: password123

-   Click the login button. The login will fail, but the data has
    already been sent across the network.

    <img width="1920" height="1080" alt="Screenshot (74)" src="https://github.com/user-attachments/assets/7047ef1e-5ebb-47f6-8d23-249b65a345ce" />

    <img width="1920" height="1080" alt="Screenshot (75)" src="https://github.com/user-attachments/assets/756f9e5d-28f4-4f0c-8958-38ad2a7f7c6a" />



**step 3: Stop Capture and Filter Traffic**

-   Return to Wireshark and click the Stop button (the red square).

-   In the display filter bar, you need to find the packet containing
    the login data. Since the form data was sent to the server, we will
    look for an HTTP POST request.

-   Apply the following filter to find the exact packet and press Enter:

-   <img width="1920" height="1080" alt="Screenshot (76)" src="https://github.com/user-attachments/assets/70eef26f-e94e-4964-b1ff-0b23fbd6d80f" />


**step 4: Inspect the Packet to Find Credentials**

-   In the filtered packet list, you should see a packet with
    information like \"POST /userinfo.php\". Select this packet.

-   In the Packet Details pane below the list, expand the following
    sections:

    <img width="1920" height="1080" alt="Screenshot (77)" src="https://github.com/user-attachments/assets/ab59a76d-794b-4f70-8e10-a91982d7c8af" />


Hypertext Transfer Protocol HTML Form URL EncodedInside the \"HTML Form
URL Encoded\" section, you will see the credentials you entered in
plaintext.

<img width="1603" height="880" alt="Screenshot 2025-08-31 223412" src="https://github.com/user-attachments/assets/8ea23552-2541-4d43-8dbb-91aeaa673625" />


**Result**

The experiment successfully intercepts the login credentials in a
human-readable format. The analysis of the captured POST packet reveals
the plaintext data that was transmitted over the network:

This result confirms the inherent security flaw of the HTTP protocol.
Any sensitive data sent over HTTP is transmitted openly, making it
trivial to intercept.
