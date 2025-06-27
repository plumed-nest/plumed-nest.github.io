**Project ID:** [plumID:23.005]({{ '/' | absolute_url }}eggs/23/005/)  
Stderr for source:  apo-5HT1A/plumed_reweight_2D_microsw_5ht1a_rec.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_5ht1a_rec.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_5ht1a_rec.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @87 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:63806] *** Process received signal ***
[pkrvmbietmlfzoi:63806] Signal: Aborted (6)
[pkrvmbietmlfzoi:63806] Signal code:  (-6)
[pkrvmbietmlfzoi:63806] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbb2b845330]
[pkrvmbietmlfzoi:63806] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbb2b89eb2c]
[pkrvmbietmlfzoi:63806] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbb2b84527e]
[pkrvmbietmlfzoi:63806] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbb2b8288ff]
[pkrvmbietmlfzoi:63806] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbb2bca5ff5]
[pkrvmbietmlfzoi:63806] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbb2bcbb0da]
[pkrvmbietmlfzoi:63806] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbb2bca5a55]
[pkrvmbietmlfzoi:63806] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbb2bca5a6f]
[pkrvmbietmlfzoi:63806] [ 8] plumed_master(+0x146dd)[0x55ee089156dd]
[pkrvmbietmlfzoi:63806] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbb2b82a1ca]
[pkrvmbietmlfzoi:63806] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbb2b82a28b]
[pkrvmbietmlfzoi:63806] [11] plumed_master(+0x15365)[0x55ee08916365]
[pkrvmbietmlfzoi:63806] *** End of error message ***
</pre>
{% endraw %}
