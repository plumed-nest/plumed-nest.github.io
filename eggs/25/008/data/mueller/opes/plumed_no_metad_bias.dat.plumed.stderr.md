**Project ID:** [plumID:25.008]({{ '/' | absolute_url }}eggs/25/008/)  
Stderr for source:  mueller/opes/plumed_no_metad_bias.dat   
Download: [zipped raw stdout](plumed_no_metad_bias.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_no_metad_bias.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
[ip-10-0-135-182:36464] *** Process received signal ***
[ip-10-0-135-182:36464] Signal: Segmentation fault (11)
[ip-10-0-135-182:36464] Signal code:  (128)
[ip-10-0-135-182:36464] Failing at address: (nil)
[ip-10-0-135-182:36464] [ 0] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x47dd0) [0x79fafc247dd0]
[ip-10-0-135-182:36464] [ 1] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail4_NFAINSt7__cxx1112regex_traitsIcEEE18_M_eliminate_dummyEv+0x47) [0x79faedab3fc7]
[ip-10-0-135-182:36464] [ 2] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail9_CompilerINSt7__cxx1112regex_traitsIcEEEC2EPKcS6_RKSt6localeNSt15regex_constants18syntax_option_typeE+0x4a8) [0x79faedac38d8]
[ip-10-0-135-182:36464] [ 3] /home/runner/opt/libtorch/lib/libc10.so(_ZN3c106DeviceC2ERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0xae2) [0x79faea21f5a2]
[ip-10-0-135-182:36464] [ 4] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler15readInstructionEv+0xfa8) [0x79faedd1a708]
[ip-10-0-135-182:36464] [ 5] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler3runEv+0xa8) [0x79faedd1ba98]
[ip-10-0-135-182:36464] [ 6] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler12parse_ivalueEv+0x2e) [0x79faedd1bcbe]
[ip-10-0-135-182:36464] [ 7] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit21readArchiveAndTensorsERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalISt8functionIFNS9_13StrongTypePtrERKNS9_13QualifiedNameEEEEENSA_ISB_IFNS9_13intrusive_ptrINS9_6ivalue6ObjectENS9_6detail34intrusive_target_default_null_typeISL_EEEESC_NS9_6IValueEEEEENSA_INS9_6DeviceEEERN6caffe29serialize19PyTorchStreamReaderE+0x471) [0x79faedcc54f1]
[ip-10-0-135-182:36464] [ 8] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c5790) [0x79faedcc5790]
[ip-10-0-135-182:36464] [ 9] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c8302) [0x79faedcc8302]
[ip-10-0-135-182:36464] [10] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadESt10shared_ptrIN6caffe29serialize20ReadAdapterInterfaceEEN3c108optionalINS6_6DeviceEEERSt13unordered_mapINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESG_St4hashISG_ESt8equal_toISG_ESaISt4pairIKSG_SG_EEE+0x1a4) [0x79faedcc8cd4]
[ip-10-0-135-182:36464] [11] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEERSt13unordered_mapIS6_S6_St4hashIS6_ESt8equal_toIS6_ESaISt4pairIS7_S6_EEE+0xc5) [0x79faedccba85]
[ip-10-0-135-182:36464] [12] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEE+0x6f) [0x79faedccbb8f]
[ip-10-0-135-182:36464] [13] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD8function7pytorch12PytorchModelC1ERKNS_13ActionOptionsE+0x4c2) [0x79fafdd1a9c2]
[ip-10-0-135-182:36464] [14] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD18ActionRegistrationINS_8function7pytorch12PytorchModelEE6createERKNS_13ActionOptionsE+0x2c) [0x79fafdd1edfc]
[ip-10-0-135-182:36464] [15] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD14ActionRegister6createERKSt6vectorIPvSaIS2_EERKNS_13ActionOptionsE+0x38e) [0x79fafd66177e]
[ip-10-0-135-182:36464] [16] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKb+0x1ce) [0x79fafd6fd4de]
[ip-10-0-135-182:36464] [17] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERNS_5IFileE+0x5e) [0x79fafd6fde2e]
[ip-10-0-135-182:36464] [18] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x9e) [0x79fafd70198e]
[ip-10-0-135-182:36464] [19] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain4initEv+0x14a7) [0x79fafd702ff7]
[ip-10-0-135-182:36464] [20] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x1d35) [0x79fafd7053a5]
[ip-10-0-135-182:36464] [21] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD7cltools6DriverIdE4mainEP8_IO_FILES4_RNS_12CommunicatorE+0x3193) [0x79fafd3905d3]
[ip-10-0-135-182:36464] [22] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10CLToolMain3runEiPPcP8_IO_FILES4_RNS_12CommunicatorE+0x1436) [0x79fafd6ad9c6]
[ip-10-0-135-182:36464] [23] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10CLToolMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0xb35) [0x79fafd6b0855]
[ip-10-0-135-182:36464] [24] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x122c) [0x79fafd70489c]
[ip-10-0-135-182:36464] [25] /home/runner/opt/lib/libplumedKernel.so(+0x90ceda) [0x79fafd70ceda]
[ip-10-0-135-182:36464] [26] plumed(+0x10f8e) [0x634a0f416f8e]
[ip-10-0-135-182:36464] [27] plumed(+0xb0d9) [0x634a0f4110d9]
[ip-10-0-135-182:36464] [28] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x2a8c1) [0x79fafc22a8c1]
[ip-10-0-135-182:36464] [29] /usr/lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x88) [0x79fafc22a9d8]
[ip-10-0-135-182:36464] *** End of error message ***
</pre>
{% endraw %}
