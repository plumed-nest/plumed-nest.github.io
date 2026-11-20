**Project ID:** [plumID:22.031]({{ '/' | absolute_url }}eggs/22/031/)  
Stderr for source:  Chignolin/unfolding/plumed_rate.dat   
Download: [zipped raw stdout](plumed_rate.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_rate.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
[runnervmccnms:28157] *** Process received signal ***
[runnervmccnms:28157] Signal: Segmentation fault (11)
[runnervmccnms:28157] Signal code:  (128)
[runnervmccnms:28157] Failing at address: (nil)
[runnervmccnms:28157] [ 0] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x47e10) [0x74d482047e10]
[runnervmccnms:28157] [ 1] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail4_NFAINSt7__cxx1112regex_traitsIcEEE18_M_eliminate_dummyEv+0x47) [0x74d4738b3fc7]
[runnervmccnms:28157] [ 2] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail9_CompilerINSt7__cxx1112regex_traitsIcEEEC2EPKcS6_RKSt6localeNSt15regex_constants18syntax_option_typeE+0x4a8) [0x74d4738c38d8]
[runnervmccnms:28157] [ 3] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e44b5) [0x74d473ae44b5]
[runnervmccnms:28157] [ 4] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e7dcc) [0x74d473ae7dcc]
[runnervmccnms:28157] [ 5] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e86fb) [0x74d473ae86fb]
[runnervmccnms:28157] [ 6] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e8b05) [0x74d473ae8b05]
[runnervmccnms:28157] [ 7] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e8bea) [0x74d473ae8bea]
[runnervmccnms:28157] [ 8] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNK5torch3jit16ScriptTypeParser17parseTypeFromExprERKNS0_4ExprE+0xc1) [0x74d473847551]
[runnervmccnms:28157] [ 9] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit16ScriptTypeParser9parseTypeERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x1f9) [0x74d473847819]
[runnervmccnms:28157] [10] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNK5torch3jit14SourceImporter8loadTypeERKN3c1013QualifiedNameE+0x4b) [0x74d473ad9bfb]
[runnervmccnms:28157] [11] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c587b) [0x74d473ac587b]
[runnervmccnms:28157] [12] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler10readGlobalERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEES9_+0x2b2) [0x74d473b15972]
[runnervmccnms:28157] [13] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler15readInstructionEv+0x61a) [0x74d473b19d7a]
[runnervmccnms:28157] [14] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler3runEv+0xa8) [0x74d473b1ba98]
[runnervmccnms:28157] [15] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler12parse_ivalueEv+0x2e) [0x74d473b1bcbe]
[runnervmccnms:28157] [16] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit21readArchiveAndTensorsERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalISt8functionIFNS9_13StrongTypePtrERKNS9_13QualifiedNameEEEEENSA_ISB_IFNS9_13intrusive_ptrINS9_6ivalue6ObjectENS9_6detail34intrusive_target_default_null_typeISL_EEEESC_NS9_6IValueEEEEENSA_INS9_6DeviceEEERN6caffe29serialize19PyTorchStreamReaderE+0x471) [0x74d473ac54f1]
[runnervmccnms:28157] [17] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c5790) [0x74d473ac5790]
[runnervmccnms:28157] [18] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c8637) [0x74d473ac8637]
[runnervmccnms:28157] [19] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadESt10shared_ptrIN6caffe29serialize20ReadAdapterInterfaceEEN3c108optionalINS6_6DeviceEEERSt13unordered_mapINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESG_St4hashISG_ESt8equal_toISG_ESaISt4pairIKSG_SG_EEE+0x1a4) [0x74d473ac8cd4]
[runnervmccnms:28157] [20] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEERSt13unordered_mapIS6_S6_St4hashIS6_ESt8equal_toIS6_ESaISt4pairIS7_S6_EEE+0xc5) [0x74d473acba85]
[runnervmccnms:28157] [21] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEE+0x6f) [0x74d473acbb8f]
[runnervmccnms:28157] [22] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD8function7pytorch12PytorchModelC1ERKNS_13ActionOptionsE+0x4c2) [0x74d483b1a9c2]
[runnervmccnms:28157] [23] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD18ActionRegistrationINS_8function7pytorch12PytorchModelEE6createERKNS_13ActionOptionsE+0x2c) [0x74d483b1edfc]
[runnervmccnms:28157] [24] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD14ActionRegister6createERKSt6vectorIPvSaIS2_EERKNS_13ActionOptionsE+0x38e) [0x74d48346177e]
[runnervmccnms:28157] [25] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKb+0x1ce) [0x74d4834fd4de]
[runnervmccnms:28157] [26] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERNS_5IFileE+0x5e) [0x74d4834fde2e]
[runnervmccnms:28157] [27] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x9e) [0x74d48350198e]
[runnervmccnms:28157] [28] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain4initEv+0x14a7) [0x74d483502ff7]
[runnervmccnms:28157] [29] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x1d35) [0x74d4835053a5]
[runnervmccnms:28157] *** End of error message ***
</pre>
{% endraw %}
