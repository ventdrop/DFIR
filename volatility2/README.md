Volatility2 profiles created using the method described in this blog: https://andreafortuna.org/2019/08/22/how-to-generate-a-volatility-profile-for-a-linux-system/

Place required .zip file in this folder (may differ on your system)
Usual location:
```python
volatility/plugins/overlays/linux/ 
```
Remnux location:
```python
/usr/local/lib/python2.7/dist-packages/volatility/plugins/overlays/linux/
```

To test installation on remnux:
```python
vol.py --info | grep "Linux"
```