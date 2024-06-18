**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
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
[fv-az1215-453:05041] *** Process received signal ***
[fv-az1215-453:05041] Signal: Aborted (6)
[fv-az1215-453:05041] Signal code:  (-6)
[fv-az1215-453:05041] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f5c45042520]
[fv-az1215-453:05041] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f5c450969fc]
[fv-az1215-453:05041] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f5c45042476]
[fv-az1215-453:05041] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f5c450287f3]
[fv-az1215-453:05041] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f5c454a2b9e]
[fv-az1215-453:05041] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f5c454ae20c]
[fv-az1215-453:05041] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f5c454ae277]
[fv-az1215-453:05041] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f5c454ae52b]
[fv-az1215-453:05041] [ 8] plumed(+0x12f48)[0x5557e6d59f48]
[fv-az1215-453:05041] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f5c45029d90]
[fv-az1215-453:05041] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f5c45029e40]
[fv-az1215-453:05041] [11] plumed(+0x131e5)[0x5557e6d5a1e5]
[fv-az1215-453:05041] *** End of error message ***
</pre>
{% endraw %}
