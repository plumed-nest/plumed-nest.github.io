**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/2_D/plumed_reweight.dat   
(download [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ITRE LABEL=it ARG=cc.logweights TEMP=1 MAXITER=20
Maybe a missing space or a typo?
[fv-az95-172:55705] *** Process received signal ***
[fv-az95-172:55705] Signal: Aborted (6)
[fv-az95-172:55705] Signal code:  (-6)
[fv-az95-172:55705] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f0ceef00210]
[fv-az95-172:55705] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f0ceef0018b]
[fv-az95-172:55705] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f0ceeedf859]
[fv-az95-172:55705] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f0cef167911]
[fv-az95-172:55705] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f0cef17338c]
[fv-az95-172:55705] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f0cef1733f7]
[fv-az95-172:55705] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f0cef1736a9]
[fv-az95-172:55705] [ 7] plumed(+0xf47d)[0x55fda435247d]
[fv-az95-172:55705] [ 8] plumed(+0x14004)[0x55fda4357004]
[fv-az95-172:55705] [ 9] plumed(+0xf698)[0x55fda4352698]
[fv-az95-172:55705] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f0ceeee10b3]
[fv-az95-172:55705] [11] plumed(+0xf76e)[0x55fda435276e]
[fv-az95-172:55705] *** End of error message ***
</pre>
{% endraw %}
