 How to Download and Set Up Hugo v0.79.1 Extended on macOS

This guide provides instructions for downloading, extracting, and installing Hugo v0.79.1 extended version on macOS.

## Steps

### 1. Download the Hugo Archive
- Go to the [Hugo releases page](https://github.com/gohugoio/hugo/releases).
- Locate version `v0.79.1`.
- Download the `hugo_extended_0.79.1_macOS-64bit.tar.gz` file to your `Downloads` folder.

### 2. Extract the Archive
- Open a Terminal and navigate to the Downloads folder:
  ```bash
  cd ~/Downloads
  ```
- Extract the contents of the `.tar.gz` file:
  ```bash
  tar -xzf hugo_extended_0.79.1_macOS-64bit.tar.gz
  ```
- This will place the `hugo` binary in the Downloads folder.

### 3. Move the Hugo Binary to the System Path
- Move the `hugo` binary to `/usr/local/bin` to make it accessible system-wide:
  ```bash
  sudo mv ~/Downloads/hugo /usr/local/bin/hugo
  ```
- Enter your password if prompted.

### 4. Grant Permissions to Terminal (If Needed)
- Open **System Settings** > **Privacy & Security**.
- Ensure that **App Download Permissions** is set to "Allow apps downloaded from: App Store and identified developers".

### 5. Verify the Installation
- Check that Hugo is correctly installed by running:
  ```bash
  hugo version
  ```
- This command should display `Hugo v0.79.1` if the setup was successful.

---

You’re now ready to use Hugo v0.79.1 on your macOS system.


