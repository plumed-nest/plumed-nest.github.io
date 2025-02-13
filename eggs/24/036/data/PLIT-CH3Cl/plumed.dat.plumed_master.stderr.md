**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-CH3Cl/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[fv-az1693-854:05708] *** Process received signal ***
[fv-az1693-854:05708] Signal: Aborted (6)
[fv-az1693-854:05708] Signal code:  (-6)
[fv-az1693-854:05708] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbaa7845330]
[fv-az1693-854:05708] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbaa789eb2c]
[fv-az1693-854:05708] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbaa784527e]
[fv-az1693-854:05708] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbaa78288ff]
[fv-az1693-854:05708] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbaa7ca5ff5]
[fv-az1693-854:05708] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbaa7cbb0da]
[fv-az1693-854:05708] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbaa7ca5a55]
[fv-az1693-854:05708] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbaa7ca5a6f]
[fv-az1693-854:05708] [ 8] plumed_master(+0x146dd)[0x5628c8cab6dd]
[fv-az1693-854:05708] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbaa782a1ca]
[fv-az1693-854:05708] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbaa782a28b]
[fv-az1693-854:05708] [11] plumed_master(+0x15365)[0x5628c8cac365]
[fv-az1693-854:05708] *** End of error message ***
</pre>
{% endraw %}
