# IT Solutions Pro - Troubleshooting Guide: Wi-Fi Connectivity

This guide provides detailed steps for diagnosing common Wi-Fi issues.

---

### Problem: My laptop can't connect to the "ITSP-Corp" Wi-Fi network.

**Troubleshooting Steps:**

1.  **Verify Wi-Fi is Enabled:** Ensure your laptop's Wi-Fi is turned on. Some laptops have a physical switch or a keyboard shortcut (e.g., `Fn + F12`).

2.  **Restart Your Device:** A simple reboot can often resolve temporary connection glitches.

3.  **Forget and Reconnect to the Network:** Go to your Wi-Fi settings, "forget" the "ITSP-Corp" network, and then reconnect using the correct password.

4.  **Check Network Adapter Drivers:** Outdated network drivers can cause connection issues.
    * Open the **Device Manager**.
    * Expand **Network adapters**.
    * Right-click on your Wi-Fi adapter and select **Update driver**.
    * Choose "Search automatically for drivers."

5.  **Run Network Troubleshooter:**
    * **Windows:** Go to **Settings > Network & Internet > Status > Network troubleshooter**.
    * **macOS:** Open **System Settings > Network** and look for a diagnostic tool.

6.  **Static IP Issue:** If you have a static IP address configured, ensure it is within the correct subnet range. If you are a remote user and have a static IP set, you must change the setting to "Obtain an IP address automatically" or "DHCP" to connect to any network.
