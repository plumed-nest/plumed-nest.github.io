**Project ID:** [plumID:25.009]({{ '/' | absolute_url }}eggs/25/009/)  
Stderr for source:  T1_MetaD/hills/plumed-reweight-time-dependent-w1.dat   
Download: [zipped raw stdout](plumed-reweight-time-dependent-w1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-reweight-time-dependent-w1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @33 : keyword ARG is compulsory for this action
[fv-az1050-229:60906] *** Process received signal ***
[fv-az1050-229:60906] Signal: Aborted (6)
[fv-az1050-229:60906] Signal code:  (-6)
[fv-az1050-229:60906] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7feb0a245330]
[fv-az1050-229:60906] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7feb0a29eb2c]
[fv-az1050-229:60906] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7feb0a24527e]
[fv-az1050-229:60906] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7feb0a2288ff]
[fv-az1050-229:60906] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7feb0a6a5ff5]
[fv-az1050-229:60906] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7feb0a6bb0da]
[fv-az1050-229:60906] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7feb0a6a5a55]
[fv-az1050-229:60906] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7feb0a6a5a6f]
[fv-az1050-229:60906] [ 8] plumed_master(+0x146dd)[0x5623682776dd]
[fv-az1050-229:60906] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7feb0a22a1ca]
[fv-az1050-229:60906] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7feb0a22a28b]
[fv-az1050-229:60906] [11] plumed_master(+0x15365)[0x562368278365]
[fv-az1050-229:60906] *** End of error message ***
</pre>
{% endraw %}
