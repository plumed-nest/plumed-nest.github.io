**Project ID:** [plumID:22.031]({{ '/' | absolute_url }}eggs/22/031/)  
Stderr for source:  Chignolin/unfolding/plumed_rate.dat   
Download: [zipped raw stdout](plumed_rate.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_rate.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
[ip-10-0-135-182:38117] *** Process received signal ***
[ip-10-0-135-182:38117] Signal: Segmentation fault (11)
[ip-10-0-135-182:38117] Signal code:  (128)
[ip-10-0-135-182:38117] Failing at address: (nil)
[ip-10-0-135-182:38117] [ 0] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x47dd0) [0x7e68f8a47dd0]
[ip-10-0-135-182:38117] [ 1] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail4_NFAINSt7__cxx1112regex_traitsIcEEE18_M_eliminate_dummyEv+0x47) [0x7e68ea2b3fc7]
[ip-10-0-135-182:38117] [ 2] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail9_CompilerINSt7__cxx1112regex_traitsIcEEEC2EPKcS6_RKSt6localeNSt15regex_constants18syntax_option_typeE+0x4a8) [0x7e68ea2c38d8]
[ip-10-0-135-182:38117] [ 3] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e44b5) [0x7e68ea4e44b5]
[ip-10-0-135-182:38117] [ 4] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e7dcc) [0x7e68ea4e7dcc]
[ip-10-0-135-182:38117] [ 5] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e86fb) [0x7e68ea4e86fb]
[ip-10-0-135-182:38117] [ 6] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e8b05) [0x7e68ea4e8b05]
[ip-10-0-135-182:38117] [ 7] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e8bea) [0x7e68ea4e8bea]
[ip-10-0-135-182:38117] [ 8] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNK5torch3jit16ScriptTypeParser17parseTypeFromExprERKNS0_4ExprE+0xc1) [0x7e68ea247551]
[ip-10-0-135-182:38117] [ 9] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit16ScriptTypeParser9parseTypeERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x1f9) [0x7e68ea247819]
[ip-10-0-135-182:38117] [10] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNK5torch3jit14SourceImporter8loadTypeERKN3c1013QualifiedNameE+0x4b) [0x7e68ea4d9bfb]
[ip-10-0-135-182:38117] [11] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c587b) [0x7e68ea4c587b]
[ip-10-0-135-182:38117] [12] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler10readGlobalERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEES9_+0x2b2) [0x7e68ea515972]
[ip-10-0-135-182:38117] [13] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler15readInstructionEv+0x61a) [0x7e68ea519d7a]
[ip-10-0-135-182:38117] [14] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler3runEv+0xa8) [0x7e68ea51ba98]
[ip-10-0-135-182:38117] [15] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler12parse_ivalueEv+0x2e) [0x7e68ea51bcbe]
[ip-10-0-135-182:38117] [16] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit21readArchiveAndTensorsERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalISt8functionIFNS9_13StrongTypePtrERKNS9_13QualifiedNameEEEEENSA_ISB_IFNS9_13intrusive_ptrINS9_6ivalue6ObjectENS9_6detail34intrusive_target_default_null_typeISL_EEEESC_NS9_6IValueEEEEENSA_INS9_6DeviceEEERN6caffe29serialize19PyTorchStreamReaderE+0x471) [0x7e68ea4c54f1]
[ip-10-0-135-182:38117] [17] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c5790) [0x7e68ea4c5790]
[ip-10-0-135-182:38117] [18] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c8637) [0x7e68ea4c8637]
[ip-10-0-135-182:38117] [19] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadESt10shared_ptrIN6caffe29serialize20ReadAdapterInterfaceEEN3c108optionalINS6_6DeviceEEERSt13unordered_mapINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESG_St4hashISG_ESt8equal_toISG_ESaISt4pairIKSG_SG_EEE+0x1a4) [0x7e68ea4c8cd4]
[ip-10-0-135-182:38117] [20] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEERSt13unordered_mapIS6_S6_St4hashIS6_ESt8equal_toIS6_ESaISt4pairIS7_S6_EEE+0xc5) [0x7e68ea4cba85]
[ip-10-0-135-182:38117] [21] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEE+0x6f) [0x7e68ea4cbb8f]
[ip-10-0-135-182:38117] [22] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD8function7pytorch12PytorchModelC1ERKNS_13ActionOptionsE+0x4ca) [0x7e68fa7b35aa]
[ip-10-0-135-182:38117] [23] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD18ActionRegistrationINS_8function7pytorch12PytorchModelEE6createERKNS_13ActionOptionsE+0x2c) [0x7e68fa7b7a3c]
[ip-10-0-135-182:38117] [24] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD14ActionRegister6createERKSt6vectorIPvSaIS2_EERKNS_13ActionOptionsE+0x284) [0x7e68f9ff0204]
[ip-10-0-135-182:38117] [25] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKb+0x17e) [0x7e68fa0c2a6e]
[ip-10-0-135-182:38117] [26] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain13readInputFileERNS_5IFileE+0x5e) [0x7e68fa0c302e]
[ip-10-0-135-182:38117] [27] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain13readInputFileERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0xa1) [0x7e68fa0ca4d1]
[ip-10-0-135-182:38117] [28] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain4initEv+0x1928) [0x7e68fa0cbfb8]
[ip-10-0-135-182:38117] [29] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x22a8) [0x7e68fa0ce998]
[ip-10-0-135-182:38117] *** End of error message ***
</pre>
{% endraw %}
