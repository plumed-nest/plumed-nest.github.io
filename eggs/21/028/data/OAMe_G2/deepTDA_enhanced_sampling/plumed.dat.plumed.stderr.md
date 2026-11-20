**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  OAMe_G2/deepTDA_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
[runnervmccnms:30692] *** Process received signal ***
[runnervmccnms:30692] Signal: Segmentation fault (11)
[runnervmccnms:30692] Signal code:  (128)
[runnervmccnms:30692] Failing at address: (nil)
[runnervmccnms:30692] [ 0] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x47e10) [0x742080c47e10]
[runnervmccnms:30692] [ 1] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail4_NFAINSt7__cxx1112regex_traitsIcEEE18_M_eliminate_dummyEv+0x47) [0x7420724b3fc7]
[runnervmccnms:30692] [ 2] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail9_CompilerINSt7__cxx1112regex_traitsIcEEEC2EPKcS6_RKSt6localeNSt15regex_constants18syntax_option_typeE+0x4a8) [0x7420724c38d8]
[runnervmccnms:30692] [ 3] /home/runner/opt/libtorch/lib/libc10.so(_ZN3c106DeviceC2ERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0xae2) [0x74206ec1f5a2]
[runnervmccnms:30692] [ 4] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler15readInstructionEv+0xfa8) [0x74207271a708]
[runnervmccnms:30692] [ 5] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler3runEv+0xa8) [0x74207271ba98]
[runnervmccnms:30692] [ 6] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler12parse_ivalueEv+0x2e) [0x74207271bcbe]
[runnervmccnms:30692] [ 7] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit21readArchiveAndTensorsERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalISt8functionIFNS9_13StrongTypePtrERKNS9_13QualifiedNameEEEEENSA_ISB_IFNS9_13intrusive_ptrINS9_6ivalue6ObjectENS9_6detail34intrusive_target_default_null_typeISL_EEEESC_NS9_6IValueEEEEENSA_INS9_6DeviceEEERN6caffe29serialize19PyTorchStreamReaderE+0x471) [0x7420726c54f1]
[runnervmccnms:30692] [ 8] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c5790) [0x7420726c5790]
[runnervmccnms:30692] [ 9] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c8302) [0x7420726c8302]
[runnervmccnms:30692] [10] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadESt10shared_ptrIN6caffe29serialize20ReadAdapterInterfaceEEN3c108optionalINS6_6DeviceEEERSt13unordered_mapINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESG_St4hashISG_ESt8equal_toISG_ESaISt4pairIKSG_SG_EEE+0x1a4) [0x7420726c8cd4]
[runnervmccnms:30692] [11] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEERSt13unordered_mapIS6_S6_St4hashIS6_ESt8equal_toIS6_ESaISt4pairIS7_S6_EEE+0xc5) [0x7420726cba85]
[runnervmccnms:30692] [12] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEE+0x6f) [0x7420726cbb8f]
[runnervmccnms:30692] [13] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD8function7pytorch12PytorchModelC1ERKNS_13ActionOptionsE+0x4c2) [0x74208271a9c2]
[runnervmccnms:30692] [14] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD18ActionRegistrationINS_8function7pytorch12PytorchModelEE6createERKNS_13ActionOptionsE+0x2c) [0x74208271edfc]
[runnervmccnms:30692] [15] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD14ActionRegister6createERKSt6vectorIPvSaIS2_EERKNS_13ActionOptionsE+0x38e) [0x74208206177e]
[runnervmccnms:30692] [16] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKb+0x1ce) [0x7420820fd4de]
[runnervmccnms:30692] [17] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERNS_5IFileE+0x5e) [0x7420820fde2e]
[runnervmccnms:30692] [18] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x9e) [0x74208210198e]
[runnervmccnms:30692] [19] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain4initEv+0x14a7) [0x742082102ff7]
[runnervmccnms:30692] [20] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x1d35) [0x7420821053a5]
[runnervmccnms:30692] [21] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD7cltools6DriverIdE4mainEP8_IO_FILES4_RNS_12CommunicatorE+0x3193) [0x742081d905d3]
[runnervmccnms:30692] [22] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10CLToolMain3runEiPPcP8_IO_FILES4_RNS_12CommunicatorE+0x1436) [0x7420820ad9c6]
[runnervmccnms:30692] [23] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10CLToolMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0xb35) [0x7420820b0855]
[runnervmccnms:30692] [24] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x122c) [0x74208210489c]
[runnervmccnms:30692] [25] /home/runner/opt/lib/libplumedKernel.so(+0x90ceda) [0x74208210ceda]
[runnervmccnms:30692] [26] plumed(+0x10f8e) [0x56a649028f8e]
[runnervmccnms:30692] [27] plumed(+0xb0d9) [0x56a6490230d9]
[runnervmccnms:30692] [28] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x2a8c1) [0x742080c2a8c1]
[runnervmccnms:30692] [29] /usr/lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x88) [0x742080c2a9d8]
[runnervmccnms:30692] *** End of error message ***
</pre>
{% endraw %}
