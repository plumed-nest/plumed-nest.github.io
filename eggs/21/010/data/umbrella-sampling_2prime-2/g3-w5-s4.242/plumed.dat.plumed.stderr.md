**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2prime-2/g3-w5-s4.242/plumed.dat   
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
[fv-az95-172:40435] *** Process received signal ***
[fv-az95-172:40435] Signal: Aborted (6)
[fv-az95-172:40435] Signal code:  (-6)
[fv-az95-172:40435] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fb672d1e210]
[fv-az95-172:40435] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fb672d1e18b]
[fv-az95-172:40435] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fb672cfd859]
[fv-az95-172:40435] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fb672f85911]
[fv-az95-172:40435] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fb672f9138c]
[fv-az95-172:40435] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fb672f913f7]
[fv-az95-172:40435] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fb672f916a9]
[fv-az95-172:40435] [ 7] plumed(+0xf47d)[0x564ebe1ee47d]
[fv-az95-172:40435] [ 8] plumed(+0x14004)[0x564ebe1f3004]
[fv-az95-172:40435] [ 9] plumed(+0xf698)[0x564ebe1ee698]
[fv-az95-172:40435] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fb672cff0b3]
[fv-az95-172:40435] [11] plumed(+0xf76e)[0x564ebe1ee76e]
[fv-az95-172:40435] *** End of error message ***
</pre>
{% endraw %}
