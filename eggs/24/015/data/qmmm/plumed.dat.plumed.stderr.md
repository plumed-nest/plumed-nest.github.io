**Project ID:** [plumID:24.015]({{ '/' | absolute_url }}eggs/24/015/)  
Stderr for source:  qmmm/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: PATHCV LABEL=pcv ARG=d1,d2,d3,d4,d5,d6,d7 INFILE=path.input
Maybe a missing space or a typo?
[fv-az530-623:03941] *** Process received signal ***
[fv-az530-623:03941] Signal: Aborted (6)
[fv-az530-623:03941] Signal code:  (-6)
[fv-az530-623:03941] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7868442520]
[fv-az530-623:03941] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f78684969fc]
[fv-az530-623:03941] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7868442476]
[fv-az530-623:03941] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f78684287f3]
[fv-az530-623:03941] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f78688a2b9e]
[fv-az530-623:03941] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f78688ae20c]
[fv-az530-623:03941] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f78688ae277]
[fv-az530-623:03941] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f78688ae52b]
[fv-az530-623:03941] [ 8] plumed(+0x12f48)[0x55682aeeff48]
[fv-az530-623:03941] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7868429d90]
[fv-az530-623:03941] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7868429e40]
[fv-az530-623:03941] [11] plumed(+0x131e5)[0x55682aef01e5]
[fv-az530-623:03941] *** End of error message ***
</pre>
{% endraw %}
