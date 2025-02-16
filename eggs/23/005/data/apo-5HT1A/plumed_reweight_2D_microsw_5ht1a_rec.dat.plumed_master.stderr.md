**Project ID:** [plumID:23.005]({{ '/' | absolute_url }}eggs/23/005/)  
Stderr for source:  apo-5HT1A/plumed_reweight_2D_microsw_5ht1a_rec.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_5ht1a_rec.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_5ht1a_rec.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @90 : keyword ARG is compulsory for this action
[fv-az1937-158:63449] *** Process received signal ***
[fv-az1937-158:63449] Signal: Aborted (6)
[fv-az1937-158:63449] Signal code:  (-6)
[fv-az1937-158:63449] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4dc3845330]
[fv-az1937-158:63449] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4dc389eb2c]
[fv-az1937-158:63449] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4dc384527e]
[fv-az1937-158:63449] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4dc38288ff]
[fv-az1937-158:63449] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4dc3ca5ff5]
[fv-az1937-158:63449] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4dc3cbb0da]
[fv-az1937-158:63449] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4dc3ca5a55]
[fv-az1937-158:63449] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4dc3ca5a6f]
[fv-az1937-158:63449] [ 8] plumed_master(+0x146dd)[0x559cc150d6dd]
[fv-az1937-158:63449] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4dc382a1ca]
[fv-az1937-158:63449] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4dc382a28b]
[fv-az1937-158:63449] [11] plumed_master(+0x15365)[0x559cc150e365]
[fv-az1937-158:63449] *** End of error message ***
</pre>
{% endraw %}
