# ColabCPPMagic - IPython extension to run C++ code in Google Colab

## Instalation
In a code cel of your Colab notebook, execute the following command:

```
!pip install git+git://github.com/almeidafranci/colab-cpp-magic.git
```

Then load the extension:

```
%load_ext colab_cpp_magic
```

You're now ready to run C++ code.

## Usage
To run C++ code, just type '%%cpp' in the beginning of the cell you want to run. Here is a simple Hello World example for you:

```
%%cpp
#include <iostream>

int main()
{
  std::cout << "Hello World!";
}
```

Have fun!
