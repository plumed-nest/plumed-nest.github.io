**Project ID:** [plumID:19.004]({{ '/' | absolute_url }}eggs/19/004/)  
Stderr for source:  MI-UBQ/8REP/plumed_8REP.dat   
(download [zipped raw stdout](plumed_8REP.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:129, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (cs\.cb-.*)
[fv-az95-172:72976] *** Process received signal ***
[fv-az95-172:72976] Signal: Aborted (6)
[fv-az95-172:72976] Signal code:  (-6)
[fv-az95-172:72976] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f9dde532210]
[fv-az95-172:72976] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f9dde53218b]
[fv-az95-172:72976] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f9dde511859]
[fv-az95-172:72976] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f9dde799911]
[fv-az95-172:72976] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f9dde7a538c]
[fv-az95-172:72976] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f9dde7a53f7]
[fv-az95-172:72976] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f9dde7a56a9]
[fv-az95-172:72976] [ 7] plumed(+0xf47d)[0x55ebbee9847d]
[fv-az95-172:72976] [ 8] plumed(+0x14004)[0x55ebbee9d004]
[fv-az95-172:72976] [ 9] plumed(+0xf698)[0x55ebbee98698]
[fv-az95-172:72976] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f9dde5130b3]
[fv-az95-172:72976] [11] plumed(+0xf76e)[0x55ebbee9876e]
[fv-az95-172:72976] *** End of error message ***
</pre>
{% endraw %}
