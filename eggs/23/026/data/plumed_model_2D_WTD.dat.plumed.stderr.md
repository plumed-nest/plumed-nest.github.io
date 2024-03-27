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
[fv-az1210-136:67774] *** Process received signal ***
[fv-az1210-136:67774] Signal: Aborted (6)
[fv-az1210-136:67774] Signal code:  (-6)
[fv-az1210-136:67774] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f995be42520]
[fv-az1210-136:67774] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f995be969fc]
[fv-az1210-136:67774] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f995be42476]
[fv-az1210-136:67774] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f995be287f3]
[fv-az1210-136:67774] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f995c2a4f26]
[fv-az1210-136:67774] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f995c2b6d9c]
[fv-az1210-136:67774] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f995c2b6e07]
[fv-az1210-136:67774] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f995c2b70bb]
[fv-az1210-136:67774] [ 8] plumed(+0x12f48)[0x562cfdbe3f48]
[fv-az1210-136:67774] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f995be29d90]
[fv-az1210-136:67774] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f995be29e40]
[fv-az1210-136:67774] [11] plumed(+0x131e5)[0x562cfdbe41e5]
[fv-az1210-136:67774] *** End of error message ***
</pre>
{% endraw %}
