**Project ID:** [plumID:23.026]({{ '/' | absolute_url }}eggs/23/026/)  
Stderr for source:  plumed_model_2D_WTD.dat   
Download: [zipped raw stdout](plumed_model_2D_WTD.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_model_2D_WTD.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: PYTHONCV LABEL=cv1 ATOMS=1-421 IMPORT=model_2D FUNCTION=cv1 COMPONENTS=ncl,nq6
Maybe a missing space or a typo?
[fv-az693-738:04109] *** Process received signal ***
[fv-az693-738:04109] Signal: Aborted (6)
[fv-az693-738:04109] Signal code:  (-6)
[fv-az693-738:04109] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7feb24842520]
[fv-az693-738:04109] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7feb248969fc]
[fv-az693-738:04109] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7feb24842476]
[fv-az693-738:04109] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7feb248287f3]
[fv-az693-738:04109] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7feb24ca2b9e]
[fv-az693-738:04109] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7feb24cae20c]
[fv-az693-738:04109] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7feb24cae277]
[fv-az693-738:04109] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7feb24cae52b]
[fv-az693-738:04109] [ 8] plumed(+0x12f48)[0x564a66bcff48]
[fv-az693-738:04109] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7feb24829d90]
[fv-az693-738:04109] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7feb24829e40]
[fv-az693-738:04109] [11] plumed(+0x131e5)[0x564a66bd01e5]
[fv-az693-738:04109] *** End of error message ***
</pre>
{% endraw %}
