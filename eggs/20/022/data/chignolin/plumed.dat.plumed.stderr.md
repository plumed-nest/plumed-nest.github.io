**Project ID:** [plumID:20.022]({{ '/' | absolute_url }}eggs/20/022/)  
Stderr for source:  chignolin/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=ene,vol MIN_TEMP=270 MAX_TEMP=800 PRESSURE=0.06022140857*2000 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857*4000 CUT_CORNER=500,0.06022140857,800,0.06022140857*1000
Maybe a missing space or a typo?
[fv-az95-172:51416] *** Process received signal ***
[fv-az95-172:51416] Signal: Aborted (6)
[fv-az95-172:51416] Signal code:  (-6)
[fv-az95-172:51416] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f84ef484210]
[fv-az95-172:51416] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f84ef48418b]
[fv-az95-172:51416] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f84ef463859]
[fv-az95-172:51416] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f84ef6eb911]
[fv-az95-172:51416] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f84ef6f738c]
[fv-az95-172:51416] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f84ef6f73f7]
[fv-az95-172:51416] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f84ef6f76a9]
[fv-az95-172:51416] [ 7] plumed(+0xf47d)[0x5603efb0747d]
[fv-az95-172:51416] [ 8] plumed(+0x14004)[0x5603efb0c004]
[fv-az95-172:51416] [ 9] plumed(+0xf698)[0x5603efb07698]
[fv-az95-172:51416] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f84ef4650b3]
[fv-az95-172:51416] [11] plumed(+0xf76e)[0x5603efb0776e]
[fv-az95-172:51416] *** End of error message ***
</pre>
{% endraw %}
