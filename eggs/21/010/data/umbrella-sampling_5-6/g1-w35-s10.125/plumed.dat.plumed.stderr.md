**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g1-w35-s10.125/plumed.dat   
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
[fv-az95-172:43897] *** Process received signal ***
[fv-az95-172:43897] Signal: Aborted (6)
[fv-az95-172:43897] Signal code:  (-6)
[fv-az95-172:43897] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f9e37378210]
[fv-az95-172:43897] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f9e3737818b]
[fv-az95-172:43897] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f9e37357859]
[fv-az95-172:43897] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f9e375df911]
[fv-az95-172:43897] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f9e375eb38c]
[fv-az95-172:43897] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f9e375eb3f7]
[fv-az95-172:43897] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f9e375eb6a9]
[fv-az95-172:43897] [ 7] plumed(+0xf47d)[0x5640fc82247d]
[fv-az95-172:43897] [ 8] plumed(+0x14004)[0x5640fc827004]
[fv-az95-172:43897] [ 9] plumed(+0xf698)[0x5640fc822698]
[fv-az95-172:43897] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f9e373590b3]
[fv-az95-172:43897] [11] plumed(+0xf76e)[0x5640fc82276e]
[fv-az95-172:43897] *** End of error message ***
</pre>
{% endraw %}
