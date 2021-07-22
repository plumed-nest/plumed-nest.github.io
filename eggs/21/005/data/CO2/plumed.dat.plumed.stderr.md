**Project ID:** [plumID:21.005]({{ '/' | absolute_url }}eggs/21/005/)  
Stderr for source:  CO2/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PYTORCH_MODEL LABEL=auto1 MODEL=co2_333_sfO_tc1.pt ARG=so.Sk3_-3_-3,so.Sk3_-3_3,so.Sk3_3_-3,so.Sk3_3_3,so.Sk0_3_-6,so.Sk0_3_6,so.Sk0_6_-3,so.Sk0_6_3,so.Sk3_-6_0,so.Sk3_0_-6,so.Sk3_0_6,so.Sk3_6_0,so.Sk6_-3_0,so.Sk6_0_-3,so.Sk6_0_3,so.Sk6_3_0,so.Sk3_-6_-3,so.Sk3_-6_3,so.Sk3_-3_-6,so.Sk3_-3_6,so.Sk3_3_-6,so.Sk3_3_6,so.Sk3_6_-3,so.Sk3_6_3,so.Sk6_-3_-3,so.Sk6_-3_3,so.Sk6_3_-3,so.Sk6_3_3,so.Sk0_6_-9,so.Sk0_6_9,so.Sk0_9_-6,so.Sk0_9_6,so.Sk6_-9_0,so.Sk6_0_-9,so.Sk6_0_9,so.Sk6_9_0,so.Sk9_-6_0,so.Sk9_0_-6,so.Sk9_0_6,so.Sk9_6_0,so.Sk3_-9_-6,so.Sk3_-9_6,so.Sk3_-6_-9,so.Sk3_-6_9,so.Sk3_6_-9,so.Sk3_6_9,so.Sk3_9_-6,so.Sk3_9_6,so.Sk6_-9_-3,so.Sk6_-9_3,so.Sk6_-3_-9,so.Sk6_-3_9,so.Sk6_3_-9,so.Sk6_3_9,so.Sk6_9_-3,so.Sk6_9_3,so.Sk9_-6_-3,so.Sk9_-6_3,so.Sk9_-3_-6,so.Sk9_-3_6,so.Sk9_3_-6,so.Sk9_3_6,so.Sk9_6_-3,so.Sk9_6_3,so.Sk0_0_12,so.Sk0_12_0,so.Sk12_0_0
Maybe a missing space or a typo?
[fv-az95-172:46489] *** Process received signal ***
[fv-az95-172:46489] Signal: Aborted (6)
[fv-az95-172:46489] Signal code:  (-6)
[fv-az95-172:46489] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f644cfc5210]
[fv-az95-172:46489] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f644cfc518b]
[fv-az95-172:46489] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f644cfa4859]
[fv-az95-172:46489] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f644d22c911]
[fv-az95-172:46489] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f644d23838c]
[fv-az95-172:46489] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f644d2383f7]
[fv-az95-172:46489] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f644d2386a9]
[fv-az95-172:46489] [ 7] plumed(+0xf47d)[0x55fe5a22b47d]
[fv-az95-172:46489] [ 8] plumed(+0x14004)[0x55fe5a230004]
[fv-az95-172:46489] [ 9] plumed(+0xf698)[0x55fe5a22b698]
[fv-az95-172:46489] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f644cfa60b3]
[fv-az95-172:46489] [11] plumed(+0xf76e)[0x55fe5a22b76e]
[fv-az95-172:46489] *** End of error message ***
</pre>
{% endraw %}
