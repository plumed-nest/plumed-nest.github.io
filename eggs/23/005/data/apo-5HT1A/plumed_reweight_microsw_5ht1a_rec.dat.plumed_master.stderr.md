**Project ID:** [plumID:23.005]({{ '/' | absolute_url }}eggs/23/005/)  
Stderr for source:  apo-5HT1A/plumed_reweight_microsw_5ht1a_rec.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @113 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:10492] *** Process received signal ***
[pkrvmbietmlfzoi:10492] Signal: Aborted (6)
[pkrvmbietmlfzoi:10492] Signal code:  (-6)
[pkrvmbietmlfzoi:10492] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2d4c245330]
[pkrvmbietmlfzoi:10492] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2d4c29eb2c]
[pkrvmbietmlfzoi:10492] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2d4c24527e]
[pkrvmbietmlfzoi:10492] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2d4c2288ff]
[pkrvmbietmlfzoi:10492] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2d4c6a5ff5]
[pkrvmbietmlfzoi:10492] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2d4c6bb0da]
[pkrvmbietmlfzoi:10492] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2d4c6a5a55]
[pkrvmbietmlfzoi:10492] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2d4c6a5a6f]
[pkrvmbietmlfzoi:10492] [ 8] plumed_master(+0x146dd)[0x555fe8db56dd]
[pkrvmbietmlfzoi:10492] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2d4c22a1ca]
[pkrvmbietmlfzoi:10492] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2d4c22a28b]
[pkrvmbietmlfzoi:10492] [11] plumed_master(+0x15365)[0x555fe8db6365]
[pkrvmbietmlfzoi:10492] *** End of error message ***
</pre>
{% endraw %}
