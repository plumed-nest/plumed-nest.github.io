**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_2D_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @87 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:06951] *** Process received signal ***
[pkrvmbietmlfzoi:06951] Signal: Aborted (6)
[pkrvmbietmlfzoi:06951] Signal code:  (-6)
[pkrvmbietmlfzoi:06951] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1966845330]
[pkrvmbietmlfzoi:06951] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f196689eb2c]
[pkrvmbietmlfzoi:06951] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f196684527e]
[pkrvmbietmlfzoi:06951] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f19668288ff]
[pkrvmbietmlfzoi:06951] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1966ca5ff5]
[pkrvmbietmlfzoi:06951] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1966cbb0da]
[pkrvmbietmlfzoi:06951] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1966ca5a55]
[pkrvmbietmlfzoi:06951] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1966ca5a6f]
[pkrvmbietmlfzoi:06951] [ 8] plumed_master(+0x146dd)[0x55fa9486c6dd]
[pkrvmbietmlfzoi:06951] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f196682a1ca]
[pkrvmbietmlfzoi:06951] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f196682a28b]
[pkrvmbietmlfzoi:06951] [11] plumed_master(+0x15365)[0x55fa9486d365]
[pkrvmbietmlfzoi:06951] *** End of error message ***
</pre>
{% endraw %}
