# 🖥️ neardesk - Run AI agents across many computers

[![Download neardesk](https://img.shields.io/badge/Download_neardesk-blue.svg)](https://github.com/muhammadsaqib-ops/neardesk)

neardesk allows you to connect multiple Windows computers together. You manage your AI coding tasks from one laptop. Your other computers act as local workers on your home network. This setup saves time by sharing the work across your hardware.

## 🚀 How it works

The software uses your local area network (LAN) to talk to other machines. You install the program on your main laptop and the machines you want to use as workers. Once connected, your laptop sends commands to these workers. The workers handle the processing tasks. This setup keeps your data on your local network. You do not need to send your code to outside servers.

## 🛠️ System requirements

Before you begin, ensure your computers meet these standards:
- Windows 10 or Windows 11.
- A stable connection to your home network via Wi-Fi or Ethernet.
- At least 4GB of RAM on each worker machine.
- Enabled remote features on your worker machines to allow network connections.

## 📥 Installing neardesk

Follow these steps to set up the software:

1. Visit [this page](https://github.com/muhammadsaqib-ops/neardesk) to download the installer.
2. Select the file ending in `.exe` for Windows.
3. Save the file to your desktop.
4. Double-click the file to start the installation.
5. Follow the on-screen prompts to complete the setup.
6. Repeat these steps on every computer you plan to use.

## ⚙️ Setting up your workers

You must prepare your helper computers to accept commands. 

1. Open the neardesk application on the helper computer.
2. Navigate to the settings menu.
3. Look for the network discovery toggle.
4. Switch this toggle to the on position.
5. Note the unique ID displayed on the screen. You will need this for your main laptop.
6. Ensure the firewall settings allow the neardesk application through. Windows may show a pop-up window asking for permission. Select Yes to allow access on private networks.

## 💻 Controlling workers from your laptop

Now you connect your laptop to the helper machines.

1. Open neardesk on your main laptop.
2. Go to the worker management tab.
3. Click the add button to include a new machine.
4. Enter the unique ID you saved from the helper computer.
5. The application will search the network for the worker.
6. Once the status changes to green, your machine is ready to accept commands.

## 📋 Managing coding agents

After your hardware connects, you can start tasks.

1. Select the task tab in the interface.
2. Choose the worker machines you want to include in the task.
3. Upload your project folder to the main laptop.
4. Click the start task button.
5. The system distributes the workload across the chosen machines.
6. You monitor the progress through the status dashboard. 

## 🔍 Troubleshooting connection issues

If you encounter a problem, check these items first:

- Network Connection: Are both computers connected to the same router? Even if they connect to different mesh nodes, they must share the same network address range.
- Firewall Settings: Sometimes security software blocks local connections. Check your security settings to ensure neardesk has access to local network traffic.
- Version Compatibility: Ensure you use the same version of neardesk on every computer. Mismatched versions can lead to errors.
- Restarting Services: If a worker does not appear, close the app on the worker machine and open it again. This forces the device to re-announce itself on the network.

## 🛡️ Security and local privacy

neardesk keeps all your work on your personal equipment. It does not store your code on a cloud server or a third-party site. Because it communicates over your local ethernet or Wi-Fi, your data never leaves your home. You maintain full control over the information because the software relies on your local network infrastructure.

## 💡 Best practices for performance

To get the most out of your hardware, consider these tips:

- Use wired connections for the worker machines if possible. Cabled internet provides a more stable link than wireless.
- Limit the number of background apps running on worker machines. This gives the AI agents more processing power.
- Organize your projects into small, distinct folders before you start a task. This helps the system distribute work more efficiently.
- Keep your windows updated. Use the Windows update tool periodically to ensure your networking drivers remain current.

## ❔ Frequently asked questions

Can I use this over the internet?
The software works best on a local network. Using it over the internet requires advanced networking knowledge and is not supported by default.

Does it work with Mac or Linux?
The current version focuses on the Windows environment. 

Will it slow down my laptop?
Your main laptop acts as a manager. It sends instructions, so it should not experience heavy performance drops.

What if my router is slow?
A standard home router handles local traffic well. Unless you process massive data sets, the speed of your router should be sufficient for most coding agent tasks.