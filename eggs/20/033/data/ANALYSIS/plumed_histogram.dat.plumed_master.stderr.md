**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  ANALYSIS/plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @30 : keyword ARG is compulsory for this action
[fv-az1911-722:08699] *** Process received signal ***
[fv-az1911-722:08699] Signal: Aborted (6)
[fv-az1911-722:08699] Signal code:  (-6)
[fv-az1911-722:08699] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa4c2645330]
[fv-az1911-722:08699] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa4c269eb2c]
[fv-az1911-722:08699] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa4c264527e]
[fv-az1911-722:08699] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa4c26288ff]
[fv-az1911-722:08699] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa4c2aa5ff5]
[fv-az1911-722:08699] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa4c2abb0da]
[fv-az1911-722:08699] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa4c2aa5a55]
[fv-az1911-722:08699] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa4c2aa5a6f]
[fv-az1911-722:08699] [ 8] plumed_master(+0x146dd)[0x55a68b2e36dd]
[fv-az1911-722:08699] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa4c262a1ca]
[fv-az1911-722:08699] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa4c262a28b]
[fv-az1911-722:08699] [11] plumed_master(+0x15365)[0x55a68b2e4365]
[fv-az1911-722:08699] *** End of error message ***
</pre>
{% endraw %}
