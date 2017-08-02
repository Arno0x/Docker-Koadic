### Koadic Docker image
  
Written by @zerosum0x0: Koadic, or COM Command & Control, is a Windows post-exploitation rootkit similar to other penetration testing tools such as Meterpreter and Powershell Empire. The major difference is that Koadic does most of its operations using Windows Script Host (a.k.a. JScript/VBScript), with compatibility in the core to support a default installation of Windows 2000 with no service packs (and potentially even versions of NT4) all the way through Windows 10.

To start the image in interactive mode:
  
`docker run --rm -ti -p 9996-9999:9996-9999 arno0x0x/koadic`
  
Project official repository is here: [Koadic on GitHub](https://github.com/zerosum0x0/koadic)