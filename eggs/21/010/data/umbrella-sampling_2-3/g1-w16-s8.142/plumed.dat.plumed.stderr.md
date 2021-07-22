**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2-3/g1-w16-s8.142/plumed.dat   
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
[fv-az95-172:38963] *** Process received signal ***
[fv-az95-172:38963] Signal: Aborted (6)
[fv-az95-172:38963] Signal code:  (-6)
[fv-az95-172:38963] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fcae51ff210]
[fv-az95-172:38963] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fcae51ff18b]
[fv-az95-172:38963] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fcae51de859]
[fv-az95-172:38963] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fcae5466911]
[fv-az95-172:38963] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fcae547238c]
[fv-az95-172:38963] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fcae54723f7]
[fv-az95-172:38963] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fcae54726a9]
[fv-az95-172:38963] [ 7] plumed(+0xf47d)[0x5615f352447d]
[fv-az95-172:38963] [ 8] plumed(+0x14004)[0x5615f3529004]
[fv-az95-172:38963] [ 9] plumed(+0xf698)[0x5615f3524698]
[fv-az95-172:38963] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fcae51e00b3]
[fv-az95-172:38963] [11] plumed(+0xf76e)[0x5615f352476e]
[fv-az95-172:38963] *** End of error message ***
</pre>
{% endraw %}
