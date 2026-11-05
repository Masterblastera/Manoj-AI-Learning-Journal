\# My Python Setup Notes



\## Check Python



```bash

python --version

```



Output:



```text

Python 3.15.2

```



\## Check UV



```bash

uv --version

```



\## Check Git



```bash

git --version

```



\## Check VS Code



```bash

code --version

```



\## Python Troubleshooting



Python was installed but Git Bash couldn't find it.



Temporary fix:



```bash

export PATH="/c/Users/user/AppData/Local/Programs/Python/Python315:$PATH"

```



Permanent fix:



```bash

echo 'export PATH="/c/Users/user/AppData/Local/Programs/Python/Python315:$PATH"' >> \~/.bashrc

```



Reload:



```bash

source \~/.bashrc

```



Verify:



```bash

python --version

```



Output:



```text

Python 3.15.2

```

