**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/3_D/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:986) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&, const bool&)
ERROR
I cannot understand line: ITRE LABEL=it ARG=cc.logweights TEMP=1 MAXITER=20
Maybe a missing space or a typo?
[fv-az1487-606:73738] *** Process received signal ***
[fv-az1487-606:73738] Signal: Aborted (6)
[fv-az1487-606:73738] Signal code:  (-6)
[fv-az1487-606:73738] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fc964042520]
[fv-az1487-606:73738] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fc9640969fc]
[fv-az1487-606:73738] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fc964042476]
[fv-az1487-606:73738] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fc9640287f3]
[fv-az1487-606:73738] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fc9644a4f26]
[fv-az1487-606:73738] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fc9644b6d9c]
[fv-az1487-606:73738] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fc9644b6e07]
[fv-az1487-606:73738] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fc9644b70bb]
[fv-az1487-606:73738] [ 8] plumed_master(+0x12e7f)[0x557dde71ae7f]
[fv-az1487-606:73738] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fc964029d90]
[fv-az1487-606:73738] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fc964029e40]
[fv-az1487-606:73738] [11] plumed_master(+0x13115)[0x557dde71b115]
[fv-az1487-606:73738] *** End of error message ***
</pre>
{% endraw %}
