# Deep Security Remote Support

Official Windows distribution repository for Deep Security Remote Support.

## Download

Download the newest signed Windows executable from [Releases](https://github.com/jtl90il/Deep-Remote-Support-Public/releases/latest).

This application supports Windows 10 and Windows 11. It connects to `https://support.deepsecurity.io` using HTTPS and secure WebSockets over TCP 443. TCP 80 is used only for redirecting to HTTPS and certificate validation.

## Security

- Confirm the Windows digital signature identifies Deep Security before running the installer.
- Release update manifests include a SHA-256 digest and a separate cryptographic signature.
- Never download the application from a third-party mirror.
- A visible notification appears when a remote support session connects.
- The user can stop the interactive support component to end the session.

The server, technician console, deployment configuration, and private development history are intentionally maintained in a separate private repository.

For security concerns, contact `Info@DeepSecurity.io`.
