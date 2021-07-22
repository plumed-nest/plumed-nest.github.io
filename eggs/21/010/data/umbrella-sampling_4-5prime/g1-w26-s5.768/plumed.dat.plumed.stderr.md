**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w26-s5.768/plumed.dat   
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
[fv-az95-172:42053] *** Process received signal ***
[fv-az95-172:42053] Signal: Aborted (6)
[fv-az95-172:42053] Signal code:  (-6)
[fv-az95-172:42053] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f126dcd1210]
[fv-az95-172:42053] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f126dcd118b]
[fv-az95-172:42053] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f126dcb0859]
[fv-az95-172:42053] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f126df38911]
[fv-az95-172:42053] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f126df4438c]
[fv-az95-172:42053] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f126df443f7]
[fv-az95-172:42053] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f126df446a9]
[fv-az95-172:42053] [ 7] plumed(+0xf47d)[0x5634d5fdc47d]
[fv-az95-172:42053] [ 8] plumed(+0x14004)[0x5634d5fe1004]
[fv-az95-172:42053] [ 9] plumed(+0xf698)[0x5634d5fdc698]
[fv-az95-172:42053] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f126dcb20b3]
[fv-az95-172:42053] [11] plumed(+0xf76e)[0x5634d5fdc76e]
[fv-az95-172:42053] *** End of error message ***
</pre>
{% endraw %}
