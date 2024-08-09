**Project ID:** [plumID:23.026]({{ '/' | absolute_url }}eggs/23/026/)  
Stderr for source:  plumed_model_pulling.dat   
Download: [zipped raw stdout](plumed_model_pulling.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_model_pulling.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: PYTHONCV LABEL=cv1 ATOMS=1-421 IMPORT=model FUNCTION=cv1
Maybe a missing space or a typo?
[fv-az693-738:04140] *** Process received signal ***
[fv-az693-738:04140] Signal: Aborted (6)
[fv-az693-738:04140] Signal code:  (-6)
[fv-az693-738:04140] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f04ffa42520]
[fv-az693-738:04140] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f04ffa969fc]
[fv-az693-738:04140] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f04ffa42476]
[fv-az693-738:04140] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f04ffa287f3]
[fv-az693-738:04140] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f04ffea2b9e]
[fv-az693-738:04140] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f04ffeae20c]
[fv-az693-738:04140] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f04ffeae277]
[fv-az693-738:04140] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f04ffeae52b]
[fv-az693-738:04140] [ 8] plumed(+0x12f48)[0x55c3c6703f48]
[fv-az693-738:04140] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f04ffa29d90]
[fv-az693-738:04140] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f04ffa29e40]
[fv-az693-738:04140] [11] plumed(+0x131e5)[0x55c3c67041e5]
[fv-az693-738:04140] *** End of error message ***
</pre>
{% endraw %}
