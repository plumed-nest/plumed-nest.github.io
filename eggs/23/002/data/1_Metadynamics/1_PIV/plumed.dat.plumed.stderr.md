**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/1_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: PAIRENTROPY LABEL=s ATOMS=1-4394 MAXR=2.5 SIGMA=0.05 NLIST NL_CUTOFF=2.8 NL_STRIDE=10
Maybe a missing space or a typo?
[fv-az1215-453:04946] *** Process received signal ***
[fv-az1215-453:04946] Signal: Aborted (6)
[fv-az1215-453:04946] Signal code:  (-6)
[fv-az1215-453:04946] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f953aa42520]
[fv-az1215-453:04946] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f953aa969fc]
[fv-az1215-453:04946] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f953aa42476]
[fv-az1215-453:04946] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f953aa287f3]
[fv-az1215-453:04946] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f953aea2b9e]
[fv-az1215-453:04946] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f953aeae20c]
[fv-az1215-453:04946] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f953aeae277]
[fv-az1215-453:04946] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f953aeae52b]
[fv-az1215-453:04946] [ 8] plumed(+0x12f48)[0x55f93c9b6f48]
[fv-az1215-453:04946] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f953aa29d90]
[fv-az1215-453:04946] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f953aa29e40]
[fv-az1215-453:04946] [11] plumed(+0x131e5)[0x55f93c9b71e5]
[fv-az1215-453:04946] *** End of error message ***
</pre>
{% endraw %}
