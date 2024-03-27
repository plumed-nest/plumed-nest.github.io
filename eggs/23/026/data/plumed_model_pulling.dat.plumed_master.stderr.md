**Project ID:** [plumID:23.026]({{ '/' | absolute_url }}eggs/23/026/)  
Stderr for source:  plumed_model_pulling.dat   
Download: [zipped raw stdout](plumed_model_pulling.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_model_pulling.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:986) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&, const bool&)
ERROR
I cannot understand line: PYTHONCV LABEL=cv1 ATOMS=1-421 IMPORT=model FUNCTION=cv1
Maybe a missing space or a typo?
[fv-az1210-136:67813] *** Process received signal ***
[fv-az1210-136:67813] Signal: Aborted (6)
[fv-az1210-136:67813] Signal code:  (-6)
[fv-az1210-136:67813] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3577642520]
[fv-az1210-136:67813] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f35776969fc]
[fv-az1210-136:67813] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3577642476]
[fv-az1210-136:67813] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f35776287f3]
[fv-az1210-136:67813] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f3577aa4f26]
[fv-az1210-136:67813] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f3577ab6d9c]
[fv-az1210-136:67813] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f3577ab6e07]
[fv-az1210-136:67813] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f3577ab70bb]
[fv-az1210-136:67813] [ 8] plumed_master(+0x12e7f)[0x55aaede32e7f]
[fv-az1210-136:67813] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3577629d90]
[fv-az1210-136:67813] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3577629e40]
[fv-az1210-136:67813] [11] plumed_master(+0x13115)[0x55aaede33115]
[fv-az1210-136:67813] *** End of error message ***
</pre>
{% endraw %}
