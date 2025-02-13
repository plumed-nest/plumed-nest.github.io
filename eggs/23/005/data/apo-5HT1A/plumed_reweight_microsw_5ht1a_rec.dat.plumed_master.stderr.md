**Project ID:** [plumID:23.005]({{ '/' | absolute_url }}eggs/23/005/)  
Stderr for source:  apo-5HT1A/plumed_reweight_microsw_5ht1a_rec.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @117 : keyword ARG is compulsory for this action
[fv-az1390-170:06166] *** Process received signal ***
[fv-az1390-170:06166] Signal: Aborted (6)
[fv-az1390-170:06166] Signal code:  (-6)
[fv-az1390-170:06166] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe81f245330]
[fv-az1390-170:06166] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe81f29eb2c]
[fv-az1390-170:06166] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe81f24527e]
[fv-az1390-170:06166] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe81f2288ff]
[fv-az1390-170:06166] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe81f6a5ff5]
[fv-az1390-170:06166] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe81f6bb0da]
[fv-az1390-170:06166] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe81f6a5a55]
[fv-az1390-170:06166] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe81f6a5a6f]
[fv-az1390-170:06166] [ 8] plumed_master(+0x146dd)[0x55eac67466dd]
[fv-az1390-170:06166] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe81f22a1ca]
[fv-az1390-170:06166] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe81f22a28b]
[fv-az1390-170:06166] [11] plumed_master(+0x15365)[0x55eac6747365]
[fv-az1390-170:06166] *** End of error message ***
</pre>
{% endraw %}
