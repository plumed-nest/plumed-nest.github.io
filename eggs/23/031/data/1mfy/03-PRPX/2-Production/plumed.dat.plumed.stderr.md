**Project ID:** [plumID:23.031]({{ '/' | absolute_url }}eggs/23/031/)  
Stderr for source:  1mfy/03-PRPX/2-Production/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: SHADOW LABEL=rmsd ATOMS=rna NOPBC UPDATE=100
Maybe a missing space or a typo?
[fv-az1272-851:05455] *** Process received signal ***
[fv-az1272-851:05455] Signal: Aborted (6)
[fv-az1272-851:05455] Signal code:  (-6)
[fv-az1272-851:05455] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f5435a42520]
[fv-az1272-851:05455] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f5435a969fc]
[fv-az1272-851:05455] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f5435a42476]
[fv-az1272-851:05455] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f5435a287f3]
[fv-az1272-851:05455] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f5435ea2b9e]
[fv-az1272-851:05455] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f5435eae20c]
[fv-az1272-851:05455] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f5435eae277]
[fv-az1272-851:05455] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f5435eae52b]
[fv-az1272-851:05455] [ 8] plumed(+0x12f48)[0x55ea1796df48]
[fv-az1272-851:05455] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f5435a29d90]
[fv-az1272-851:05455] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f5435a29e40]
[fv-az1272-851:05455] [11] plumed(+0x131e5)[0x55ea1796e1e5]
[fv-az1272-851:05455] *** End of error message ***
</pre>
{% endraw %}
