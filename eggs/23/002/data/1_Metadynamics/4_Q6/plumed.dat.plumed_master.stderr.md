**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
[fv-az1781-845:62046] *** Process received signal ***
[fv-az1781-845:62046] Signal: Segmentation fault (11)
[fv-az1781-845:62046] Signal code:  (128)
[fv-az1781-845:62046] Failing at address: (nil)
[fv-az1781-845:62046] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5202245330]
[fv-az1781-845:62046] [ 1] /home/runner/opt/lib/libplumed_masterKernel.so(_ZNK4PLMD8Keywords6existsESt17basic_string_viewIcSt11char_traitsIcEE+0x90)[0x7f520392ace0]
[fv-az1781-845:62046] [ 2] /home/runner/opt/lib/libplumed_masterKernel.so(_ZNK4PLMD6Action5errorERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x46)[0x7f52031478c6]
[fv-az1781-845:62046] [ 3] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD6Action9checkReadEv+0x47d)[0x7f5203147d7d]
[fv-az1781-845:62046] [ 4] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKb+0x294)[0x7f52031e1114]
[fv-az1781-845:62046] [ 5] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD7cltools6DriverIdE4mainEP8_IO_FILES4_RNS_12CommunicatorE+0x6f90)[0x7f5202ec8660]
[fv-az1781-845:62046] [ 6] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10CLToolMain3runEiPPcP8_IO_FILES4_RNS_12CommunicatorE+0x5e2)[0x7f520319bbc2]
[fv-az1781-845:62046] [ 7] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10CLToolMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x470)[0x7f520319ee70]
[fv-az1781-845:62046] [ 8] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x141b)[0x7f52031eba0b]
[fv-az1781-845:62046] [ 9] /home/runner/opt/lib/libplumed_masterKernel.so(+0x7f43f1)[0x7f52031f43f1]
[fv-az1781-845:62046] [10] plumed_master(+0x1eb37)[0x55c30d5bab37]
[fv-az1781-845:62046] [11] plumed_master(+0x1521d)[0x55c30d5b121d]
[fv-az1781-845:62046] [12] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f520222a1ca]
[fv-az1781-845:62046] [13] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f520222a28b]
[fv-az1781-845:62046] [14] plumed_master(+0x15365)[0x55c30d5b1365]
[fv-az1781-845:62046] *** End of error message ***
</pre>
{% endraw %}
