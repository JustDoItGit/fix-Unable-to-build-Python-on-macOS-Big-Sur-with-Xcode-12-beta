# fix-Unable-to-build-Python-on-macOS-Big-Sur-with-Xcode-12-beta

## My computer configuration
iMac (Retina 5K, 27-inch, 2019)  
3 GHz 六核Intel Core i5  
I formaed the hard drive, then reinstall the system big sur.

## This is a screenshot of my process
![image](https://github.com/LearningChanging/fix-Unable-to-build-Python-on-macOS-Big-Sur-with-Xcode-12-beta/blob/main/images/inporcess_image.png)

## this is my readline zx zblib .zshrc config
```text
#If you need to have openssl@1.1 first
export PATH="/usr/local/opt/openssl@1.1/bin:$PATH"

# For compilers to find openssl@1.1
export LDFLAGS="-L/usr/local/opt/openssl@1.1/lib"
export CPPFLAGS="-I/usr/local/opt/openssl@1.1/include"

# For pkg-config to find openssl@1.1
export PKG_CONFIG_PATH="/usr/local/opt/openssl@1.1/lib/pkgconfig"

# For compilers to find readline
export LDFLAGS="-L/usr/local/opt/readline/lib"
export CPPFLAGS="-I/usr/local/opt/readline/include"

# For pkg-config to find readline
export PKG_CONFIG_PATH="/usr/local/opt/readline/lib/pkgconfig"


# For compilers to find zlib
export LDFLAGS="-L/usr/local/opt/zlib/lib"
export CPPFLAGS="-I/usr/local/opt/zlib/include"

# For pkg-config to find zlib
export PKG_CONFIG_PATH="/usr/local/opt/zlib/lib/pkgconfig"

export PATH="/usr/local/opt/sqlite/bin:$PATH"

# For compilers to find sqlite
export LDFLAGS="-L/usr/local/opt/sqlite/lib"
export CPPFLAGS="-I/usr/local/opt/sqlite/include"

# For pkg-config to find sqlite
export PKG_CONFIG_PATH="/usr/local/opt/sqlite/lib/pkgconfig" 
```
