**Project ID:** [plumID:23.005]({{ '/' | absolute_url }}eggs/23/005/)  
Stderr for source:  apo-5HT1A/plumed_reweight_microsw_5ht1a_rec.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @117 : keyword ARG is compulsory for this action
[fv-az1267-279:62647] *** Process received signal ***
[fv-az1267-279:62647] Signal: Aborted (6)
[fv-az1267-279:62647] Signal code:  (-6)
[fv-az1267-279:62647] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa00f045330]
[fv-az1267-279:62647] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa00f09eb2c]
[fv-az1267-279:62647] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa00f04527e]
[fv-az1267-279:62647] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa00f0288ff]
[fv-az1267-279:62647] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa00f4a5ff5]
[fv-az1267-279:62647] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa00f4bb0da]
[fv-az1267-279:62647] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa00f4a5a55]
[fv-az1267-279:62647] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa00f4a5a6f]
[fv-az1267-279:62647] [ 8] plumed_master(+0x146dd)[0x55e674c636dd]
[fv-az1267-279:62647] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa00f02a1ca]
[fv-az1267-279:62647] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa00f02a28b]
[fv-az1267-279:62647] [11] plumed_master(+0x15365)[0x55e674c64365]
[fv-az1267-279:62647] *** End of error message ***
</pre>
{% endraw %}
