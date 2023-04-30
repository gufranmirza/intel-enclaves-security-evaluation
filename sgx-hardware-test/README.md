# SGX-hardware list

This is a list of hardware which supports Intel SGX - Software Guard Extensions.

## Test SGX

You can check if SGX is enabled on you system with the test_sgx.c. Just compile and run it:

```
$ gcc test-sgx.c -o test-sgx
$ ./test-sgx
```

```
...
eax: 906ed ebx: 10800 ecx: feda3203 edx: f8bfbff
stepping 13
model 14
family 6
processor type 0
extended model 9
extended family 0
smx: 0

Extended feature bits (EAX=07H, ECX=0H)
eax: 0 ebx: 9c6fbd ecx: 40000000 edx: 400
sgx available: 1
sgx launch control: 1

CPUID Leaf 12H, Sub-Leaf 0 of Intel SGX Capabilities (EAX=12H,ECX=0)
eax: 1 ebx: 0 ecx: 0 edx: 241f
sgx 1 supported: 1
sgx 2 supported: 0
MaxEnclaveSize_Not64: 1f
MaxEnclaveSize_64: 24

CPUID Leaf 12H, Sub-Leaf 1 of Intel SGX Capabilities (EAX=12H,ECX=1)
eax: 36 ebx: 0 ecx: 1f edx: 0

CPUID Leaf 12H, Sub-Leaf 2 of Intel SGX Capabilities (EAX=12H,ECX=2)
eax: c0200001 ebx: 1 ecx: 1a00001 edx: 0
size of EPC section in Processor Reserved Memory, 26 M

CPUID Leaf 12H, Sub-Leaf 3 of Intel SGX Capabilities (EAX=12H,ECX=3)
eax: c1e00001 ebx: 1 ecx: 200001 edx: 0
size of EPC section in Processor Reserved Memory, 2 M

CPUID Leaf 12H, Sub-Leaf 4 of Intel SGX Capabilities (EAX=12H,ECX=4)
eax: 0 ebx: 0 ecx: 0 edx: 0
size of EPC section in Processor Reserved Memory, 0 M

CPUID Leaf 12H, Sub-Leaf 5 of Intel SGX Capabilities (EAX=12H,ECX=5)
eax: 0 ebx: 0 ecx: 0 edx: 0
size of EPC section in Processor Reserved Memory, 0 M

CPUID Leaf 12H, Sub-Leaf 6 of Intel SGX Capabilities (EAX=12H,ECX=6)
eax: 0 ebx: 0 ecx: 0 edx: 0
size of EPC section in Processor Reserved Memory, 0 M

CPUID Leaf 12H, Sub-Leaf 7 of Intel SGX Capabilities (EAX=12H,ECX=7)
eax: 0 ebx: 0 ecx: 0 edx: 0
size of EPC section in Processor Reserved Memory, 0 M

CPUID Leaf 12H, Sub-Leaf 8 of Intel SGX Capabilities (EAX=12H,ECX=8)
eax: 0 ebx: 0 ecx: 0 edx: 0
size of EPC section in Processor Reserved Memory, 0 M

CPUID Leaf 12H, Sub-Leaf 9 of Intel SGX Capabilities (EAX=12H,ECX=9)
eax: 0 ebx: 0 ecx: 0 edx: 0
size of EPC section in Processor Reserved Memory, 0 M
...
```
