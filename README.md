**1. Clone wallet sources**

```
git clone https://github.com/Jofta/JoftaCoinWallet.git
```

**2. Create git submodule:**

```
cd JoftaCoinWallet

git submodule add https://github.com/Jofta/JoftaCoin.git cryptonote
```

**4. Build**

```
mkdir build && cd build && cmake .. && make
```
