**Project ID:** [plumID:20.022]({{ '/' | absolute_url }}eggs/20/022/)  
Stderr for source:  alanine/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL LABEL=ecv ARG=ene MAX_TEMP=1000
Maybe a missing space or a typo?
[fv-az95-172:51393] *** Process received signal ***
[fv-az95-172:51393] Signal: Aborted (6)
[fv-az95-172:51393] Signal code:  (-6)
[fv-az95-172:51393] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f4bb45f5210]
[fv-az95-172:51393] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f4bb45f518b]
[fv-az95-172:51393] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f4bb45d4859]
[fv-az95-172:51393] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f4bb485c911]
[fv-az95-172:51393] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f4bb486838c]
[fv-az95-172:51393] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f4bb48683f7]
[fv-az95-172:51393] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f4bb48686a9]
[fv-az95-172:51393] [ 7] plumed(+0xf47d)[0x561345b1747d]
[fv-az95-172:51393] [ 8] plumed(+0x14004)[0x561345b1c004]
[fv-az95-172:51393] [ 9] plumed(+0xf698)[0x561345b17698]
[fv-az95-172:51393] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f4bb45d60b3]
[fv-az95-172:51393] [11] plumed(+0xf76e)[0x561345b1776e]
[fv-az95-172:51393] *** End of error message ***
</pre>
{% endraw %}
