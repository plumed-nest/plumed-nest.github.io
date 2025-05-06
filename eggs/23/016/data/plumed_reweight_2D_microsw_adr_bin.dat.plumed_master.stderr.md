**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_2D_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @90 : keyword ARG is compulsory for this action
[fv-az2209-645:61418] *** Process received signal ***
[fv-az2209-645:61418] Signal: Aborted (6)
[fv-az2209-645:61418] Signal code:  (-6)
[fv-az2209-645:61418] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f93a1045330]
[fv-az2209-645:61418] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f93a109eb2c]
[fv-az2209-645:61418] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f93a104527e]
[fv-az2209-645:61418] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f93a10288ff]
[fv-az2209-645:61418] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f93a14a5ff5]
[fv-az2209-645:61418] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f93a14bb0da]
[fv-az2209-645:61418] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f93a14a5a55]
[fv-az2209-645:61418] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f93a14a5a6f]
[fv-az2209-645:61418] [ 8] plumed_master(+0x146dd)[0x55f8b48b26dd]
[fv-az2209-645:61418] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f93a102a1ca]
[fv-az2209-645:61418] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f93a102a28b]
[fv-az2209-645:61418] [11] plumed_master(+0x15365)[0x55f8b48b3365]
[fv-az2209-645:61418] *** End of error message ***
</pre>
{% endraw %}
