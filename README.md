## Run Nexus Prover Beta (Early Access)

**Ready to contribute to the Nexus Network?** 

This guide helps you install and run the Nexus Prover Beta on your Ubuntu system (local or VPS).

**Minimum Requirements:**

* 4 GB RAM (recommended: 6 GB)

**Installation:**

1. Open your terminal.
2. Run one of these commands (choose either `curl` or `wget`):

   ```bash
   curl -sSL https://raw.githubusercontent.com/stephenahmeed/nexus-prover/main/nexus.sh | bash
   ```

   or

   ```bash
   wget -qO - https://raw.githubusercontent.com/stephenahmeed/nexus-prover/main/nexus.sh | bash
   ```

**Running the Prover:**

* **VPS:** No further action needed.
* **Local System:** The prover starts automatically on system boot. 
   * To manually start: `sudo systemctl start nexus.service`

**Checking Status:**

* `systemctl status nexus.service` (shows running/stopped status)

**Viewing Logs:**

* `journalctl -u nexus.service -f -n 50` (shows detailed logs)

**Let's contribute to the Nexus Network!**
