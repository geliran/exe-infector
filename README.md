# exe-infector
CLI written in C++ to embed an exe inside another exe.

New exe file is produced with the same icon as the original file, which contains the original file and the potentially malicious payload as resources, which are both unpacked and launched when the file is opened.

* The "malicious" payload is currently hardcoded to be a Python script (this could be an exe instead, or any other applicable format)
* This is for educational purposes only; use at your own risk
