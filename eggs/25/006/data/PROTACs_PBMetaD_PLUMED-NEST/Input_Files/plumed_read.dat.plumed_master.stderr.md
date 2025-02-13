**Project ID:** [plumID:25.006]({{ '/' | absolute_url }}eggs/25/006/)  
Stderr for source:  PROTACs_PBMetaD_PLUMED-NEST/Input_Files/plumed_read.dat   
Download: [zipped raw stdout](plumed_read.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_read.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label d_tbut_ph_brd4 : could not find file named ../colvar_distances.data
[fv-az1390-170:05480] *** Process received signal ***
[fv-az1390-170:05480] Signal: Aborted (6)
[fv-az1390-170:05480] Signal code:  (-6)
[fv-az1390-170:05480] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f51d9645330]
[fv-az1390-170:05480] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f51d969eb2c]
[fv-az1390-170:05480] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f51d964527e]
[fv-az1390-170:05480] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f51d96288ff]
[fv-az1390-170:05480] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f51d9aa5ff5]
[fv-az1390-170:05480] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f51d9abb0da]
[fv-az1390-170:05480] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f51d9aa5a55]
[fv-az1390-170:05480] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f51d9aa5a6f]
[fv-az1390-170:05480] [ 8] plumed_master(+0x146dd)[0x55925b6bc6dd]
[fv-az1390-170:05480] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f51d962a1ca]
[fv-az1390-170:05480] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f51d962a28b]
[fv-az1390-170:05480] [11] plumed_master(+0x15365)[0x55925b6bd365]
[fv-az1390-170:05480] *** End of error message ***
</pre>
{% endraw %}
