**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: MORE_THAN LABEL=flq6 ARG=lq6 SWITCH=GAUSSIAN D_0=0.19 R_0=0.01 D_MAX=0.2
Maybe a missing space or a typo?
[fv-az1215-453:08594] *** Process received signal ***
[fv-az1215-453:08594] Signal: Aborted (6)
[fv-az1215-453:08594] Signal code:  (-6)
[fv-az1215-453:08594] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f14abc42520]
[fv-az1215-453:08594] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f14abc969fc]
[fv-az1215-453:08594] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f14abc42476]
[fv-az1215-453:08594] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f14abc287f3]
[fv-az1215-453:08594] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f14ac0a2b9e]
[fv-az1215-453:08594] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f14ac0ae20c]
[fv-az1215-453:08594] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f14ac0ae277]
[fv-az1215-453:08594] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f14ac0ae52b]
[fv-az1215-453:08594] [ 8] plumed(+0x12f48)[0x564243a95f48]
[fv-az1215-453:08594] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f14abc29d90]
[fv-az1215-453:08594] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f14abc29e40]
[fv-az1215-453:08594] [11] plumed(+0x131e5)[0x564243a961e5]
[fv-az1215-453:08594] *** End of error message ***
</pre>
{% endraw %}
