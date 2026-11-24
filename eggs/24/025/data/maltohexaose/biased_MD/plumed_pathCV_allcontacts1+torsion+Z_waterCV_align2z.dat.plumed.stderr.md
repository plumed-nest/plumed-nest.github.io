**Project ID:** [plumID:24.025]({{ '/' | absolute_url }}eggs/24/025/)  
Stderr for source:  maltohexaose/biased_MD/plumed_pathCV_allcontacts1+torsion+Z_waterCV_align2z.dat   
Download: [zipped raw stdout](plumed_pathCV_allcontacts1+torsion+Z_waterCV_align2z.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_pathCV_allcontacts1+torsion+Z_waterCV_align2z.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
[runnervm0hi8g:36899] *** Process received signal ***
[runnervm0hi8g:36899] Signal: Segmentation fault (11)
[runnervm0hi8g:36899] Signal code:  (128)
[runnervm0hi8g:36899] Failing at address: (nil)
[runnervm0hi8g:36899] [ 0] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x47dd0) [0x79f7a0647dd0]
[runnervm0hi8g:36899] [ 1] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail4_NFAINSt7__cxx1112regex_traitsIcEEE18_M_eliminate_dummyEv+0x47) [0x79f791eb3fc7]
[runnervm0hi8g:36899] [ 2] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail9_CompilerINSt7__cxx1112regex_traitsIcEEEC2EPKcS6_RKSt6localeNSt15regex_constants18syntax_option_typeE+0x4a8) [0x79f791ec38d8]
[runnervm0hi8g:36899] [ 3] /home/runner/opt/libtorch/lib/libc10.so(_ZN3c106DeviceC2ERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0xae2) [0x79f78e61f5a2]
[runnervm0hi8g:36899] [ 4] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler15readInstructionEv+0xfa8) [0x79f79211a708]
[runnervm0hi8g:36899] [ 5] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler3runEv+0xa8) [0x79f79211ba98]
[runnervm0hi8g:36899] [ 6] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler12parse_ivalueEv+0x2e) [0x79f79211bcbe]
[runnervm0hi8g:36899] [ 7] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit21readArchiveAndTensorsERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalISt8functionIFNS9_13StrongTypePtrERKNS9_13QualifiedNameEEEEENSA_ISB_IFNS9_13intrusive_ptrINS9_6ivalue6ObjectENS9_6detail34intrusive_target_default_null_typeISL_EEEESC_NS9_6IValueEEEEENSA_INS9_6DeviceEEERN6caffe29serialize19PyTorchStreamReaderE+0x471) [0x79f7920c54f1]
[runnervm0hi8g:36899] [ 8] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c5790) [0x79f7920c5790]
[runnervm0hi8g:36899] [ 9] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c8302) [0x79f7920c8302]
[runnervm0hi8g:36899] [10] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadESt10shared_ptrIN6caffe29serialize20ReadAdapterInterfaceEEN3c108optionalINS6_6DeviceEEERSt13unordered_mapINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESG_St4hashISG_ESt8equal_toISG_ESaISt4pairIKSG_SG_EEE+0x1a4) [0x79f7920c8cd4]
[runnervm0hi8g:36899] [11] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEERSt13unordered_mapIS6_S6_St4hashIS6_ESt8equal_toIS6_ESaISt4pairIS7_S6_EEE+0xc5) [0x79f7920cba85]
[runnervm0hi8g:36899] [12] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEE+0x6f) [0x79f7920cbb8f]
[runnervm0hi8g:36899] [13] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD8function7pytorch12PytorchModelC1ERKNS_13ActionOptionsE+0x4c2) [0x79f7a211a9c2]
[runnervm0hi8g:36899] [14] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD18ActionRegistrationINS_8function7pytorch12PytorchModelEE6createERKNS_13ActionOptionsE+0x2c) [0x79f7a211edfc]
[runnervm0hi8g:36899] [15] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD14ActionRegister6createERKSt6vectorIPvSaIS2_EERKNS_13ActionOptionsE+0x38e) [0x79f7a1a6177e]
[runnervm0hi8g:36899] [16] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKb+0x1ce) [0x79f7a1afd4de]
[runnervm0hi8g:36899] [17] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERNS_5IFileE+0x5e) [0x79f7a1afde2e]
[runnervm0hi8g:36899] [18] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x9e) [0x79f7a1b0198e]
[runnervm0hi8g:36899] [19] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain4initEv+0x14a7) [0x79f7a1b02ff7]
[runnervm0hi8g:36899] [20] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x1d35) [0x79f7a1b053a5]
[runnervm0hi8g:36899] [21] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD7cltools6DriverIdE4mainEP8_IO_FILES4_RNS_12CommunicatorE+0x3193) [0x79f7a17905d3]
[runnervm0hi8g:36899] [22] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10CLToolMain3runEiPPcP8_IO_FILES4_RNS_12CommunicatorE+0x1436) [0x79f7a1aad9c6]
[runnervm0hi8g:36899] [23] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10CLToolMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0xb35) [0x79f7a1ab0855]
[runnervm0hi8g:36899] [24] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x122c) [0x79f7a1b0489c]
[runnervm0hi8g:36899] [25] /home/runner/opt/lib/libplumedKernel.so(+0x90ceda) [0x79f7a1b0ceda]
[runnervm0hi8g:36899] [26] plumed(+0x10f8e) [0x5d21dced2f8e]
[runnervm0hi8g:36899] [27] plumed(+0xb0d9) [0x5d21dcecd0d9]
[runnervm0hi8g:36899] [28] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x2a8c1) [0x79f7a062a8c1]
[runnervm0hi8g:36899] [29] /usr/lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x88) [0x79f7a062a9d8]
[runnervm0hi8g:36899] *** End of error message ***
</pre>
{% endraw %}
