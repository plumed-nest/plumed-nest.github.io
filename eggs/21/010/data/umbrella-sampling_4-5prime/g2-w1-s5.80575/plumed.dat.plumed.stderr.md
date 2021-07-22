**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g2-w1-s5.80575/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: HILLS RESTART HEIGHT 0.000 W_STRIDE 50
Maybe a missing space or a typo?
[fv-az95-172:43087] *** Process received signal ***
[fv-az95-172:43087] Signal: Aborted (6)
[fv-az95-172:43087] Signal code:  (-6)
[fv-az95-172:43087] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f2a0d912210]
[fv-az95-172:43087] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f2a0d91218b]
[fv-az95-172:43087] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f2a0d8f1859]
[fv-az95-172:43087] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f2a0db79911]
[fv-az95-172:43087] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f2a0db8538c]
[fv-az95-172:43087] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f2a0db853f7]
[fv-az95-172:43087] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f2a0db856a9]
[fv-az95-172:43087] [ 7] plumed(+0xf47d)[0x5580c2c7547d]
[fv-az95-172:43087] [ 8] plumed(+0x14004)[0x5580c2c7a004]
[fv-az95-172:43087] [ 9] plumed(+0xf698)[0x5580c2c75698]
[fv-az95-172:43087] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f2a0d8f30b3]
[fv-az95-172:43087] [11] plumed(+0xf76e)[0x5580c2c7576e]
[fv-az95-172:43087] *** End of error message ***
</pre>
{% endraw %}
