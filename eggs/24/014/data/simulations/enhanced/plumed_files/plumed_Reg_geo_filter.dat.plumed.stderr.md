**Project ID:** [plumID:24.014]({{ '/' | absolute_url }}eggs/24/014/)  
Stderr for source:  simulations/enhanced/plumed_files/plumed_Reg_geo_filter.dat   
Download: [zipped raw stdout](plumed_Reg_geo_filter.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Reg_geo_filter.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
[runnervmccnms:27404] *** Process received signal ***
[runnervmccnms:27404] Signal: Segmentation fault (11)
[runnervmccnms:27404] Signal code:  (128)
[runnervmccnms:27404] Failing at address: (nil)
[runnervmccnms:27404] [ 0] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x47e10) [0x77b2fbe47e10]
[runnervmccnms:27404] [ 1] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail4_NFAINSt7__cxx1112regex_traitsIcEEE18_M_eliminate_dummyEv+0x47) [0x77b2ed6b3fc7]
[runnervmccnms:27404] [ 2] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail9_CompilerINSt7__cxx1112regex_traitsIcEEEC2EPKcS6_RKSt6localeNSt15regex_constants18syntax_option_typeE+0x4a8) [0x77b2ed6c38d8]
[runnervmccnms:27404] [ 3] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e44b5) [0x77b2ed8e44b5]
[runnervmccnms:27404] [ 4] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e7dcc) [0x77b2ed8e7dcc]
[runnervmccnms:27404] [ 5] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e86fb) [0x77b2ed8e86fb]
[runnervmccnms:27404] [ 6] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e8b05) [0x77b2ed8e8b05]
[runnervmccnms:27404] [ 7] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e8bea) [0x77b2ed8e8bea]
[runnervmccnms:27404] [ 8] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNK5torch3jit16ScriptTypeParser17parseTypeFromExprERKNS0_4ExprE+0xc1) [0x77b2ed647551]
[runnervmccnms:27404] [ 9] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit16ScriptTypeParser9parseTypeERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x1f9) [0x77b2ed647819]
[runnervmccnms:27404] [10] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNK5torch3jit14SourceImporter8loadTypeERKN3c1013QualifiedNameE+0x4b) [0x77b2ed8d9bfb]
[runnervmccnms:27404] [11] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c587b) [0x77b2ed8c587b]
[runnervmccnms:27404] [12] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler10readGlobalERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEES9_+0x2b2) [0x77b2ed915972]
[runnervmccnms:27404] [13] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler15readInstructionEv+0x61a) [0x77b2ed919d7a]
[runnervmccnms:27404] [14] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler3runEv+0xa8) [0x77b2ed91ba98]
[runnervmccnms:27404] [15] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler12parse_ivalueEv+0x2e) [0x77b2ed91bcbe]
[runnervmccnms:27404] [16] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit21readArchiveAndTensorsERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalISt8functionIFNS9_13StrongTypePtrERKNS9_13QualifiedNameEEEEENSA_ISB_IFNS9_13intrusive_ptrINS9_6ivalue6ObjectENS9_6detail34intrusive_target_default_null_typeISL_EEEESC_NS9_6IValueEEEEENSA_INS9_6DeviceEEERN6caffe29serialize19PyTorchStreamReaderE+0x471) [0x77b2ed8c54f1]
[runnervmccnms:27404] [17] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c5790) [0x77b2ed8c5790]
[runnervmccnms:27404] [18] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c8637) [0x77b2ed8c8637]
[runnervmccnms:27404] [19] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadESt10shared_ptrIN6caffe29serialize20ReadAdapterInterfaceEEN3c108optionalINS6_6DeviceEEERSt13unordered_mapINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESG_St4hashISG_ESt8equal_toISG_ESaISt4pairIKSG_SG_EEE+0x1a4) [0x77b2ed8c8cd4]
[runnervmccnms:27404] [20] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEERSt13unordered_mapIS6_S6_St4hashIS6_ESt8equal_toIS6_ESaISt4pairIS7_S6_EEE+0xc5) [0x77b2ed8cba85]
[runnervmccnms:27404] [21] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEE+0x6f) [0x77b2ed8cbb8f]
[runnervmccnms:27404] [22] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD8function7pytorch12PytorchModelC1ERKNS_13ActionOptionsE+0x4c2) [0x77b2fd91a9c2]
[runnervmccnms:27404] [23] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD18ActionRegistrationINS_8function7pytorch12PytorchModelEE6createERKNS_13ActionOptionsE+0x2c) [0x77b2fd91edfc]
[runnervmccnms:27404] [24] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD14ActionRegister6createERKSt6vectorIPvSaIS2_EERKNS_13ActionOptionsE+0x38e) [0x77b2fd26177e]
[runnervmccnms:27404] [25] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKb+0x1ce) [0x77b2fd2fd4de]
[runnervmccnms:27404] [26] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERNS_5IFileE+0x5e) [0x77b2fd2fde2e]
[runnervmccnms:27404] [27] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x9e) [0x77b2fd30198e]
[runnervmccnms:27404] [28] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain4initEv+0x14a7) [0x77b2fd302ff7]
[runnervmccnms:27404] [29] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x1d35) [0x77b2fd3053a5]
[runnervmccnms:27404] *** End of error message ***
</pre>
{% endraw %}
