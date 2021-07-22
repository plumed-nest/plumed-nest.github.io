**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2prime-2/g1-w3-s5.713/plumed.dat   
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
[fv-az95-172:40068] *** Process received signal ***
[fv-az95-172:40068] Signal: Aborted (6)
[fv-az95-172:40068] Signal code:  (-6)
[fv-az95-172:40068] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fbef42dd210]
[fv-az95-172:40068] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fbef42dd18b]
[fv-az95-172:40068] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fbef42bc859]
[fv-az95-172:40068] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fbef4544911]
[fv-az95-172:40068] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fbef455038c]
[fv-az95-172:40068] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fbef45503f7]
[fv-az95-172:40068] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fbef45506a9]
[fv-az95-172:40068] [ 7] plumed(+0xf47d)[0x559c36d0547d]
[fv-az95-172:40068] [ 8] plumed(+0x14004)[0x559c36d0a004]
[fv-az95-172:40068] [ 9] plumed(+0xf698)[0x559c36d05698]
[fv-az95-172:40068] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fbef42be0b3]
[fv-az95-172:40068] [11] plumed(+0xf76e)[0x559c36d0576e]
[fv-az95-172:40068] *** End of error message ***
</pre>
{% endraw %}
