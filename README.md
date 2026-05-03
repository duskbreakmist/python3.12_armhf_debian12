# python3.12_armhf_debian12
python3.12 for armhf built bydebian12

download and uzip:
```
sudo tar -xzvpf python3.12-armhf-standalone.tar.gz -C /opt/python3.12-standalone
```
test by:
```
/opt/python3.12-standalone/bin/python3.12 -m pip --version
```

if you have UV
```
uv venv /opt/py3_12 --python /opt/python3.12-standalone/bin/python3.12
source /opt/py3_12/bin/activate
uv pip install --upgrade pip setuptools wheel
```
