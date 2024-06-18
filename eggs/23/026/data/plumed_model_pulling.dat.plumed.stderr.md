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
[fv-az695-955:04180] *** Process received signal ***
[fv-az695-955:04180] Signal: Aborted (6)
[fv-az695-955:04180] Signal code:  (-6)
[fv-az695-955:04180] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f4753842520]
[fv-az695-955:04180] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f47538969fc]
[fv-az695-955:04180] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f4753842476]
[fv-az695-955:04180] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f47538287f3]
[fv-az695-955:04180] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f4753ca2b9e]
[fv-az695-955:04180] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f4753cae20c]
[fv-az695-955:04180] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f4753cae277]
[fv-az695-955:04180] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f4753cae52b]
[fv-az695-955:04180] [ 8] plumed(+0x12f48)[0x55fd3a243f48]
[fv-az695-955:04180] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f4753829d90]
[fv-az695-955:04180] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f4753829e40]
[fv-az695-955:04180] [11] plumed(+0x131e5)[0x55fd3a2441e5]
[fv-az695-955:04180] *** End of error message ***
</pre>
{% endraw %}
