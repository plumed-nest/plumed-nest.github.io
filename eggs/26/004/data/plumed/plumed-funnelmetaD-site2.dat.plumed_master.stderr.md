**Project ID:** [plumID:26.004]({{ '/' | absolute_url }}eggs/26/004/)  
Stderr for source:  plumed/plumed-funnelmetaD-site2.dat   
Download: [zipped raw stdout](plumed-funnelmetaD-site2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-funnelmetaD-site2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
[runnervmccnms:26582] *** Process received signal ***
[runnervmccnms:26582] Signal: Segmentation fault (11)
[runnervmccnms:26582] Signal code:  (128)
[runnervmccnms:26582] Failing at address: (nil)
[runnervmccnms:26582] [ 0] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x47e10) [0x75a0a9247e10]
[runnervmccnms:26582] [ 1] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail4_NFAINSt7__cxx1112regex_traitsIcEEE18_M_eliminate_dummyEv+0x47) [0x75a09aab3fc7]
[runnervmccnms:26582] [ 2] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail9_CompilerINSt7__cxx1112regex_traitsIcEEEC2EPKcS6_RKSt6localeNSt15regex_constants18syntax_option_typeE+0x4a8) [0x75a09aac38d8]
[runnervmccnms:26582] [ 3] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e44b5) [0x75a09ace44b5]
[runnervmccnms:26582] [ 4] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e7dcc) [0x75a09ace7dcc]
[runnervmccnms:26582] [ 5] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e86fb) [0x75a09ace86fb]
[runnervmccnms:26582] [ 6] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e8b05) [0x75a09ace8b05]
[runnervmccnms:26582] [ 7] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e8bea) [0x75a09ace8bea]
[runnervmccnms:26582] [ 8] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNK5torch3jit16ScriptTypeParser17parseTypeFromExprERKNS0_4ExprE+0xc1) [0x75a09aa47551]
[runnervmccnms:26582] [ 9] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit16ScriptTypeParser9parseTypeERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x1f9) [0x75a09aa47819]
[runnervmccnms:26582] [10] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNK5torch3jit14SourceImporter8loadTypeERKN3c1013QualifiedNameE+0x4b) [0x75a09acd9bfb]
[runnervmccnms:26582] [11] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c587b) [0x75a09acc587b]
[runnervmccnms:26582] [12] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler10readGlobalERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEES9_+0x2b2) [0x75a09ad15972]
[runnervmccnms:26582] [13] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler15readInstructionEv+0x61a) [0x75a09ad19d7a]
[runnervmccnms:26582] [14] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler3runEv+0xa8) [0x75a09ad1ba98]
[runnervmccnms:26582] [15] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler12parse_ivalueEv+0x2e) [0x75a09ad1bcbe]
[runnervmccnms:26582] [16] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit21readArchiveAndTensorsERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalISt8functionIFNS9_13StrongTypePtrERKNS9_13QualifiedNameEEEEENSA_ISB_IFNS9_13intrusive_ptrINS9_6ivalue6ObjectENS9_6detail34intrusive_target_default_null_typeISL_EEEESC_NS9_6IValueEEEEENSA_INS9_6DeviceEEERN6caffe29serialize19PyTorchStreamReaderE+0x471) [0x75a09acc54f1]
[runnervmccnms:26582] [17] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c5790) [0x75a09acc5790]
[runnervmccnms:26582] [18] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c8637) [0x75a09acc8637]
[runnervmccnms:26582] [19] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadESt10shared_ptrIN6caffe29serialize20ReadAdapterInterfaceEEN3c108optionalINS6_6DeviceEEERSt13unordered_mapINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESG_St4hashISG_ESt8equal_toISG_ESaISt4pairIKSG_SG_EEE+0x1a4) [0x75a09acc8cd4]
[runnervmccnms:26582] [20] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEERSt13unordered_mapIS6_S6_St4hashIS6_ESt8equal_toIS6_ESaISt4pairIS7_S6_EEE+0xc5) [0x75a09accba85]
[runnervmccnms:26582] [21] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEE+0x6f) [0x75a09accbb8f]
[runnervmccnms:26582] [22] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD8function7pytorch12PytorchModelC1ERKNS_13ActionOptionsE+0x4ca) [0x75a0aaf80caa]
[runnervmccnms:26582] [23] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD18ActionRegistrationINS_8function7pytorch12PytorchModelEE6createERKNS_13ActionOptionsE+0x2c) [0x75a0aaf8513c]
[runnervmccnms:26582] [24] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD14ActionRegister6createERKSt6vectorIPvSaIS2_EERKNS_13ActionOptionsE+0x284) [0x75a0aa7c8054]
[runnervmccnms:26582] [25] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKb+0x17e) [0x75a0aa895fbe]
[runnervmccnms:26582] [26] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain13readInputFileERNS_5IFileE+0x5e) [0x75a0aa89656e]
[runnervmccnms:26582] [27] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain13readInputFileERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0xa1) [0x75a0aa89d391]
[runnervmccnms:26582] [28] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain4initEv+0x1428) [0x75a0aa89e978]
[runnervmccnms:26582] [29] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x2308) [0x75a0aa8a12d8]
[runnervmccnms:26582] *** End of error message ***
</pre>
{% endraw %}
