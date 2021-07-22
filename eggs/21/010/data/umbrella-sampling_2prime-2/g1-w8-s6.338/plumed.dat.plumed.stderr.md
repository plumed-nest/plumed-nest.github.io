**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2prime-2/g1-w8-s6.338/plumed.dat   
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
[fv-az95-172:40189] *** Process received signal ***
[fv-az95-172:40189] Signal: Aborted (6)
[fv-az95-172:40189] Signal code:  (-6)
[fv-az95-172:40189] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f5279565210]
[fv-az95-172:40189] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f527956518b]
[fv-az95-172:40189] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f5279544859]
[fv-az95-172:40189] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f52797cc911]
[fv-az95-172:40189] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f52797d838c]
[fv-az95-172:40189] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f52797d83f7]
[fv-az95-172:40189] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f52797d86a9]
[fv-az95-172:40189] [ 7] plumed(+0xf47d)[0x5637c1e1e47d]
[fv-az95-172:40189] [ 8] plumed(+0x14004)[0x5637c1e23004]
[fv-az95-172:40189] [ 9] plumed(+0xf698)[0x5637c1e1e698]
[fv-az95-172:40189] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f52795460b3]
[fv-az95-172:40189] [11] plumed(+0xf76e)[0x5637c1e1e76e]
[fv-az95-172:40189] *** End of error message ***
</pre>
{% endraw %}
