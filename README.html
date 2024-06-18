<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Kernel Compilation Instructions</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
        }
        h1, h2 {
            color: #333;
        }
        pre {
            background-color: #f4f4f4;
            padding: 10px;
            border: 1px solid #ddd;
            overflow-x: auto;
        }
    </style>
</head>
<body>

<h1>Kernel Compilation Instructions</h1>

<p>This document contains the necessary commands to compile the Linux kernel with specific configurations and patches.</p>

<h2>Prerequisites</h2>
<p>Ensure you have the following packages installed:</p>
<pre><code>sudo apt update
sudo apt install build-essential libncurses-dev bison flex libssl-dev libelf-dev mokutil
</code></pre>

<h2>Extract the Kernel Source</h2>
<pre><code>tar -xvf linux-6.6.32.tar.gz
cd linux-6.6.32
</code></pre>

<h2>Apply Patch</h2>
<pre><code>patch -p1 &lt; ../1.patch
</code></pre>

<h2>Configure the Kernel</h2>
<pre><code>sudo make localmodconfig
make menuconfig
</code></pre>

<h2>Optional: Configure Secure Boot Keys</h2>
<pre><code>sudo scripts/config --disable SYSTEM_TRUSTED_KEYS
sudo scripts/config --disable SYSTEM_REVOCATION_KEYS
sudo scripts/config --set-str CONFIG_SYSTEM_TRUSTED_KEYS ""
sudo scripts/config --set-str CONFIG_SYSTEM_REVOCATION_KEYS ""
</code></pre>

<h2>Build and Install the Kernel</h2>
<pre><code>sudo time make -j8 -d
sudo make modules_install
sudo make install
sudo update-grub
sudo reboot
</code></pre>

</body>
</html>
