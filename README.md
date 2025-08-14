# Identify-and-Remove-Suspicious-Browser-Extensions
 Learn to spot and remove potentially harmful browser extensions.

# 🔍 Browser Extension Security Check

## Steps

1. **Open Extension Manager**
   - Chrome: `Menu > More tools > Extensions`
   - Firefox: `Menu > Add-ons and themes > Extensions`
   - Edge: `Menu > Extensions`

2. **Review Installed Extensions**
   - Check each extension’s name, description, and developer.

3. **Check Permissions & Reviews**
   - Verify requested permissions.
   - Look up reviews and ratings online.

4. **Identify Unused or Suspicious Extensions**
   - Flag anything you don’t recognize or no longer use.

5. **Remove Suspicious/Unnecessary Extensions**
   - Click “Remove” or “Disable” in the extension manager.

6. **Restart Browser**
   - Close and reopen to apply changes.

7. **Check for Performance Improvements**
   - Test page load speed and responsiveness.

8. **Research Risks of Malicious Extensions**
   - Can steal login credentials.
   - Can track browsing activity.
   - Can inject ads or redirect websites.
   - Can install malware.
  
   - 


# Web Browser Performance Testing on Linux

This guide explains how to measure and analyze the performance of a web browser in Linux, including speed, memory usage, and responsiveness.

---

## 1. Built-in Browser Developer Tools
Most browsers have built-in profiling tools:

### Chrome / Chromium / Brave
- Press `Ctrl + Shift + I` → Go to the **Performance** tab.
- Click **Record** → Load a page or interact with it.
- Stop recording to view CPU, rendering, and scripting breakdown.

### Firefox
- Press `Ctrl + Shift + I` → **Performance** tab.
- Record a session and review the results.

---

## 2. Browser Benchmark Tests
Run these benchmarks in your browser:

- [Speedometer](https://browserbench.org/Speedometer/) — Tests web app responsiveness.
- [JetStream](https://browserbench.org/JetStream/) — Tests JavaScript & WebAssembly speed.
- [MotionMark](https://browserbench.org/MotionMark/) — Tests graphics rendering.
- [Basemark Web 3.0](https://web.basemark.com/) — Full browser performance score.

---

## 3. Monitor Resource Usage in Linux

### Install Tools
```bash
sudo apt update
sudo apt install htop sysstat iotop ps_mem -y

---

✅ **Outcome:** Browser is lighter, faster, and more secure after extension cleanup.
