**Project ID:** [plumID:19.012]({{ '/' | absolute_url }}eggs/19/012/)  
Stderr for source:  ./Protein-DNA/plumed-main.dat   
(download [zipped raw stdout](plumed-main.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:129, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (saxsdata\.biasDer)
[fv-az95-172:72448] *** Process received signal ***
[fv-az95-172:72448] Signal: Aborted (6)
[fv-az95-172:72448] Signal code:  (-6)
[fv-az95-172:72448] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f6bedf9a210]
[fv-az95-172:72448] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f6bedf9a18b]
[fv-az95-172:72448] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f6bedf79859]
[fv-az95-172:72448] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f6bee201911]
[fv-az95-172:72448] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f6bee20d38c]
[fv-az95-172:72448] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f6bee20d3f7]
[fv-az95-172:72448] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f6bee20d6a9]
[fv-az95-172:72448] [ 7] plumed(+0xf47d)[0x55faf15d047d]
[fv-az95-172:72448] [ 8] plumed(+0x14004)[0x55faf15d5004]
[fv-az95-172:72448] [ 9] plumed(+0xf698)[0x55faf15d0698]
[fv-az95-172:72448] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f6bedf7b0b3]
[fv-az95-172:72448] [11] plumed(+0xf76e)[0x55faf15d076e]
[fv-az95-172:72448] *** End of error message ***
</pre>
{% endraw %}
