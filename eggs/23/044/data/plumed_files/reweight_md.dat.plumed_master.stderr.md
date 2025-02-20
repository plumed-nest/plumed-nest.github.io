**Project ID:** [plumID:23.044]({{ '/' | absolute_url }}eggs/23/044/)  
Stderr for source:  plumed_files/reweight_md.dat   
Download: [zipped raw stdout](reweight_md.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_md.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[fv-az1911-722:05495] *** Process received signal ***
[fv-az1911-722:05495] Signal: Aborted (6)
[fv-az1911-722:05495] Signal code:  (-6)
[fv-az1911-722:05495] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7feccfc45330]
[fv-az1911-722:05495] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7feccfc9eb2c]
[fv-az1911-722:05495] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7feccfc4527e]
[fv-az1911-722:05495] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7feccfc288ff]
[fv-az1911-722:05495] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fecd00a5ff5]
[fv-az1911-722:05495] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fecd00bb0da]
[fv-az1911-722:05495] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fecd00a5a55]
[fv-az1911-722:05495] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fecd00a5a6f]
[fv-az1911-722:05495] [ 8] plumed_master(+0x146dd)[0x559d01a556dd]
[fv-az1911-722:05495] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7feccfc2a1ca]
[fv-az1911-722:05495] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7feccfc2a28b]
[fv-az1911-722:05495] [11] plumed_master(+0x15365)[0x559d01a56365]
[fv-az1911-722:05495] *** End of error message ***
</pre>
{% endraw %}
