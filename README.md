# prime-run
*a simple bash script to run apps with prime render offload*

```bash
__NV_PRIME_RENDER_OFFLOAD=1 __GLX_VENDOR_LIBRARY_NAME=nvidia "$@"
```

## Install

*make executable*

```
chmod +x prime-run
```

*add to path*
```
sudo mv prime-run /usr/bin/
```

## Usage

```bash
prime-run firefox
```
