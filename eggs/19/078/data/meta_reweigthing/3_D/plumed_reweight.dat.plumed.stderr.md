**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/3_D/plumed_reweight.dat   
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
[fv-az95-172:55776] *** Process received signal ***
[fv-az95-172:55776] Signal: Aborted (6)
[fv-az95-172:55776] Signal code:  (-6)
[fv-az95-172:55776] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f14290e0210]
[fv-az95-172:55776] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f14290e018b]
[fv-az95-172:55776] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f14290bf859]
[fv-az95-172:55776] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f1429347911]
[fv-az95-172:55776] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f142935338c]
[fv-az95-172:55776] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f14293533f7]
[fv-az95-172:55776] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f14293536a9]
[fv-az95-172:55776] [ 7] plumed(+0xf47d)[0x5587d654947d]
[fv-az95-172:55776] [ 8] plumed(+0x14004)[0x5587d654e004]
[fv-az95-172:55776] [ 9] plumed(+0xf698)[0x5587d6549698]
[fv-az95-172:55776] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f14290c10b3]
[fv-az95-172:55776] [11] plumed(+0xf76e)[0x5587d654976e]
[fv-az95-172:55776] *** End of error message ***
</pre>
{% endraw %}
