# byLeek Injector

A lightweight, stealthy, and modern Mono Framework Injection software designed for .NET game interaction. This is a fully compiled, ready-to-use version featuring a sleek dark user interface and advanced privacy bypass mechanisms.

## 🌟 Key Features

* **Modern Dark Interface:** Custom frameless flat design inspired by Discord/Visual Studio Dark aesthetics, replacing the outdated standard Windows borders.
* **Animated Splash Screen:** Elegant startup intro with smooth fade-in and fade-out animations.
* **Auto-Prefetch Cleanup (Stealth):** Built-in self-cleaning engine that completely wipes the application's `.pf` cache from `C:\Windows\Prefetch` immediately upon closing.
* **Renamed Payload Security:** Core interaction modules are dynamically linked, preventing basic signature detection.
* **Advanced Mono Hiding:** Experimental safety options to decouple and hide your injected assemblies from standard Mono domain detection logs.

## 🚀 How to Download & Run

1. Go to the **Releases** section on the right side of this GitHub page.
2. Download the latest `byLeek-Injector.zip` archive.
3. Extract the contents of the archive into a single folder on your PC.
4. Right-click the executable file and select **"Run as Administrator"** (Required for injection hooks and Prefetch self-cleaning logic).

## 🛠️ Quick Usage Guide

1. Select your target game process from the active process dropdown menu.
2. Click the `...` button to select your compiled assembly (`.dll`).
3. Fill in the exact **Namespace**, **Class**, and **Method** fields (e.g., `YourProject`, `Loader`, `Init`).
4. (Optional) Check the "Hide from AssemblyLoad Callback" option for extra stealth.
5. Click **Inject !** and check the execution status.

## ⚠️ Important System Notice

* **Administrator Rights:** The injector **MUST** be launched with Admin privileges, otherwise Windows will block memory writing operations and prevent the automated cleanup of system prefetch logs on exit.
* **Dependencies:** Keep the main `.exe` and its companion `.dll` files in the exact same directory, or the injector will fail to initialize.

## 📜 License & Copyright
Developed and optimized by **leek**. Distributed as a pre-compiled utility. Reverse engineering or redistribution under different branding without permission is strictly discouraged.
