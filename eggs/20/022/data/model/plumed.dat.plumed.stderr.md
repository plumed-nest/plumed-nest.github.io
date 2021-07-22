**Project ID:** [plumID:20.022]({{ '/' | absolute_url }}eggs/20/022/)  
Stderr for source:  model/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_UMBRELLAS_LINE LABEL=ecv ARG=p.x MIN_CV=-2.5 MAX_CV=2.5 SIGMA=0.185815
Maybe a missing space or a typo?
[fv-az95-172:51439] *** Process received signal ***
[fv-az95-172:51439] Signal: Aborted (6)
[fv-az95-172:51439] Signal code:  (-6)
[fv-az95-172:51439] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f327e5a6210]
[fv-az95-172:51439] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f327e5a618b]
[fv-az95-172:51439] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f327e585859]
[fv-az95-172:51439] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f327e80d911]
[fv-az95-172:51439] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f327e81938c]
[fv-az95-172:51439] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f327e8193f7]
[fv-az95-172:51439] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f327e8196a9]
[fv-az95-172:51439] [ 7] plumed(+0xf47d)[0x562550d8447d]
[fv-az95-172:51439] [ 8] plumed(+0x14004)[0x562550d89004]
[fv-az95-172:51439] [ 9] plumed(+0xf698)[0x562550d84698]
[fv-az95-172:51439] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f327e5870b3]
[fv-az95-172:51439] [11] plumed(+0xf76e)[0x562550d8476e]
[fv-az95-172:51439] *** End of error message ***
</pre>
{% endraw %}
