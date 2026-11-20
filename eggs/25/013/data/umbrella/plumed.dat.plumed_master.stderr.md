**Project ID:** [plumID:25.013]({{ '/' | absolute_url }}eggs/25/013/)  
Stderr for source:  umbrella/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
[ip-10-0-130-9:26665] *** Process received signal ***
[ip-10-0-130-9:26665] Signal: Segmentation fault (11)
[ip-10-0-130-9:26665] Signal code:  (128)
[ip-10-0-130-9:26665] Failing at address: (nil)
[ip-10-0-130-9:26665] [ 0] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x47e10) [0x74d4eba47e10]
[ip-10-0-130-9:26665] [ 1] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail4_NFAINSt7__cxx1112regex_traitsIcEEE18_M_eliminate_dummyEv+0x47) [0x74d4dd2b3fc7]
[ip-10-0-130-9:26665] [ 2] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail9_CompilerINSt7__cxx1112regex_traitsIcEEEC2EPKcS6_RKSt6localeNSt15regex_constants18syntax_option_typeE+0x4a8) [0x74d4dd2c38d8]
[ip-10-0-130-9:26665] [ 3] /home/runner/opt/libtorch/lib/libc10.so(_ZN3c106DeviceC2ERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0xae2) [0x74d4d9a1f5a2]
[ip-10-0-130-9:26665] [ 4] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler15readInstructionEv+0xfa8) [0x74d4dd51a708]
[ip-10-0-130-9:26665] [ 5] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler3runEv+0xa8) [0x74d4dd51ba98]
[ip-10-0-130-9:26665] [ 6] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler12parse_ivalueEv+0x2e) [0x74d4dd51bcbe]
[ip-10-0-130-9:26665] [ 7] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit21readArchiveAndTensorsERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalISt8functionIFNS9_13StrongTypePtrERKNS9_13QualifiedNameEEEEENSA_ISB_IFNS9_13intrusive_ptrINS9_6ivalue6ObjectENS9_6detail34intrusive_target_default_null_typeISL_EEEESC_NS9_6IValueEEEEENSA_INS9_6DeviceEEERN6caffe29serialize19PyTorchStreamReaderE+0x471) [0x74d4dd4c54f1]
[ip-10-0-130-9:26665] [ 8] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c5790) [0x74d4dd4c5790]
[ip-10-0-130-9:26665] [ 9] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c8302) [0x74d4dd4c8302]
[ip-10-0-130-9:26665] [10] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadESt10shared_ptrIN6caffe29serialize20ReadAdapterInterfaceEEN3c108optionalINS6_6DeviceEEERSt13unordered_mapINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESG_St4hashISG_ESt8equal_toISG_ESaISt4pairIKSG_SG_EEE+0x1a4) [0x74d4dd4c8cd4]
[ip-10-0-130-9:26665] [11] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEERSt13unordered_mapIS6_S6_St4hashIS6_ESt8equal_toIS6_ESaISt4pairIS7_S6_EEE+0xc5) [0x74d4dd4cba85]
[ip-10-0-130-9:26665] [12] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEE+0x6f) [0x74d4dd4cbb8f]
[ip-10-0-130-9:26665] [13] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD8function7pytorch12PytorchModelC1ERKNS_13ActionOptionsE+0x4ca) [0x74d4ed780caa]
[ip-10-0-130-9:26665] [14] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD18ActionRegistrationINS_8function7pytorch12PytorchModelEE6createERKNS_13ActionOptionsE+0x2c) [0x74d4ed78513c]
[ip-10-0-130-9:26665] [15] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD14ActionRegister6createERKSt6vectorIPvSaIS2_EERKNS_13ActionOptionsE+0x284) [0x74d4ecfc8054]
[ip-10-0-130-9:26665] [16] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKb+0x17e) [0x74d4ed095fbe]
[ip-10-0-130-9:26665] [17] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain13readInputFileERNS_5IFileE+0x5e) [0x74d4ed09656e]
[ip-10-0-130-9:26665] [18] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain13readInputFileERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0xa1) [0x74d4ed09d391]
[ip-10-0-130-9:26665] [19] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain4initEv+0x1428) [0x74d4ed09e978]
[ip-10-0-130-9:26665] [20] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x2308) [0x74d4ed0a12d8]
[ip-10-0-130-9:26665] [21] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD7cltools6DriverIdE4mainEP8_IO_FILES4_RNS_12CommunicatorE+0x2e47) [0x74d4ecc66247]
[ip-10-0-130-9:26665] [22] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10CLToolMain3runEiPPcP8_IO_FILES4_RNS_12CommunicatorE+0x3127) [0x74d4ed01f6c7]
[ip-10-0-130-9:26665] [23] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10CLToolMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x772) [0x74d4ed021992]
[ip-10-0-130-9:26665] [24] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x5a0c) [0x74d4ed0a49dc]
[ip-10-0-130-9:26665] [25] /home/runner/opt/lib/libplumed_masterKernel.so(+0xaaba1a) [0x74d4ed0aba1a]
[ip-10-0-130-9:26665] [26] plumed_master(+0xaecb) [0x5a06d21abecb]
[ip-10-0-130-9:26665] [27] plumed_master(+0x84bd) [0x5a06d21a94bd]
[ip-10-0-130-9:26665] [28] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x2a8c1) [0x74d4eba2a8c1]
[ip-10-0-130-9:26665] [29] /usr/lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x88) [0x74d4eba2a9d8]
[ip-10-0-130-9:26665] *** End of error message ***
</pre>
{% endraw %}
