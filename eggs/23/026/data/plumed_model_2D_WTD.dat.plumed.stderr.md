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
[fv-az695-955:04149] *** Process received signal ***
[fv-az695-955:04149] Signal: Aborted (6)
[fv-az695-955:04149] Signal code:  (-6)
[fv-az695-955:04149] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f2289c42520]
[fv-az695-955:04149] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f2289c969fc]
[fv-az695-955:04149] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f2289c42476]
[fv-az695-955:04149] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f2289c287f3]
[fv-az695-955:04149] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f228a0a2b9e]
[fv-az695-955:04149] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f228a0ae20c]
[fv-az695-955:04149] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f228a0ae277]
[fv-az695-955:04149] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f228a0ae52b]
[fv-az695-955:04149] [ 8] plumed(+0x12f48)[0x55d7c6c81f48]
[fv-az695-955:04149] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f2289c29d90]
[fv-az695-955:04149] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f2289c29e40]
[fv-az695-955:04149] [11] plumed(+0x131e5)[0x55d7c6c821e5]
[fv-az695-955:04149] *** End of error message ***
</pre>
{% endraw %}
