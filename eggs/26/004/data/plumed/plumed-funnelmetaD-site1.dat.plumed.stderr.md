**Project ID:** [plumID:26.004]({{ '/' | absolute_url }}eggs/26/004/)  
Stderr for source:  plumed/plumed-funnelmetaD-site1.dat   
Download: [zipped raw stdout](plumed-funnelmetaD-site1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-funnelmetaD-site1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
[runnervm0hi8g:36205] *** Process received signal ***
[runnervm0hi8g:36205] Signal: Segmentation fault (11)
[runnervm0hi8g:36205] Signal code: Address not mapped (1)
[runnervm0hi8g:36205] Failing at address: 0x1df3cf34f05480
[runnervm0hi8g:36205] [ 0] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x47dd0) [0x764001647dd0]
[runnervm0hi8g:36205] [ 1] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail4_NFAINSt7__cxx1112regex_traitsIcEEE18_M_eliminate_dummyEv+0x47) [0x763ff2eb3fc7]
[runnervm0hi8g:36205] [ 2] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail9_CompilerINSt7__cxx1112regex_traitsIcEEEC2EPKcS6_RKSt6localeNSt15regex_constants18syntax_option_typeE+0x4a8) [0x763ff2ec38d8]
[runnervm0hi8g:36205] [ 3] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e44b5) [0x763ff30e44b5]
[runnervm0hi8g:36205] [ 4] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e7dcc) [0x763ff30e7dcc]
[runnervm0hi8g:36205] [ 5] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e86fb) [0x763ff30e86fb]
[runnervm0hi8g:36205] [ 6] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e8b05) [0x763ff30e8b05]
[runnervm0hi8g:36205] [ 7] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e8bea) [0x763ff30e8bea]
[runnervm0hi8g:36205] [ 8] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNK5torch3jit16ScriptTypeParser17parseTypeFromExprERKNS0_4ExprE+0xc1) [0x763ff2e47551]
[runnervm0hi8g:36205] [ 9] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit16ScriptTypeParser9parseTypeERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x1f9) [0x763ff2e47819]
[runnervm0hi8g:36205] [10] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNK5torch3jit14SourceImporter8loadTypeERKN3c1013QualifiedNameE+0x4b) [0x763ff30d9bfb]
[runnervm0hi8g:36205] [11] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c587b) [0x763ff30c587b]
[runnervm0hi8g:36205] [12] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler10readGlobalERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEES9_+0x2b2) [0x763ff3115972]
[runnervm0hi8g:36205] [13] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler15readInstructionEv+0x61a) [0x763ff3119d7a]
[runnervm0hi8g:36205] [14] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler3runEv+0xa8) [0x763ff311ba98]
[runnervm0hi8g:36205] [15] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler12parse_ivalueEv+0x2e) [0x763ff311bcbe]
[runnervm0hi8g:36205] [16] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit21readArchiveAndTensorsERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalISt8functionIFNS9_13StrongTypePtrERKNS9_13QualifiedNameEEEEENSA_ISB_IFNS9_13intrusive_ptrINS9_6ivalue6ObjectENS9_6detail34intrusive_target_default_null_typeISL_EEEESC_NS9_6IValueEEEEENSA_INS9_6DeviceEEERN6caffe29serialize19PyTorchStreamReaderE+0x471) [0x763ff30c54f1]
[runnervm0hi8g:36205] [17] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c5790) [0x763ff30c5790]
[runnervm0hi8g:36205] [18] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c8637) [0x763ff30c8637]
[runnervm0hi8g:36205] [19] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadESt10shared_ptrIN6caffe29serialize20ReadAdapterInterfaceEEN3c108optionalINS6_6DeviceEEERSt13unordered_mapINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESG_St4hashISG_ESt8equal_toISG_ESaISt4pairIKSG_SG_EEE+0x1a4) [0x763ff30c8cd4]
[runnervm0hi8g:36205] [20] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEERSt13unordered_mapIS6_S6_St4hashIS6_ESt8equal_toIS6_ESaISt4pairIS7_S6_EEE+0xc5) [0x763ff30cba85]
[runnervm0hi8g:36205] [21] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEE+0x6f) [0x763ff30cbb8f]
[runnervm0hi8g:36205] [22] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD8function7pytorch12PytorchModelC1ERKNS_13ActionOptionsE+0x4c2) [0x76400311a9c2]
[runnervm0hi8g:36205] [23] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD18ActionRegistrationINS_8function7pytorch12PytorchModelEE6createERKNS_13ActionOptionsE+0x2c) [0x76400311edfc]
[runnervm0hi8g:36205] [24] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD14ActionRegister6createERKSt6vectorIPvSaIS2_EERKNS_13ActionOptionsE+0x38e) [0x764002a6177e]
[runnervm0hi8g:36205] [25] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKb+0x1ce) [0x764002afd4de]
[runnervm0hi8g:36205] [26] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERNS_5IFileE+0x5e) [0x764002afde2e]
[runnervm0hi8g:36205] [27] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x9e) [0x764002b0198e]
[runnervm0hi8g:36205] [28] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain4initEv+0x14a7) [0x764002b02ff7]
[runnervm0hi8g:36205] [29] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x1d35) [0x764002b053a5]
[runnervm0hi8g:36205] *** End of error message ***
</pre>
{% endraw %}
