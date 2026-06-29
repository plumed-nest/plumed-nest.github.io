**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[runnervmmklqx:11427] *** Process received signal ***
[runnervmmklqx:11427] Signal: Aborted (6)
[runnervmmklqx:11427] Signal code:  (-6)
[runnervmmklqx:11427] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4abe245330]
[runnervmmklqx:11427] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4abe29eb2c]
[runnervmmklqx:11427] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4abe24527e]
[runnervmmklqx:11427] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4abe2288ff]
[runnervmmklqx:11427] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4abe6a5ff5]
[runnervmmklqx:11427] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4abe6bb0da]
[runnervmmklqx:11427] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4abe6a5a55]
[runnervmmklqx:11427] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4abe6a5a6f]
[runnervmmklqx:11427] [ 8] plumed_master(+0x146dd)[0x55a40ba8e6dd]
[runnervmmklqx:11427] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4abe22a1ca]
[runnervmmklqx:11427] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4abe22a28b]
[runnervmmklqx:11427] [11] plumed_master(+0x15365)[0x55a40ba8f365]
[runnervmmklqx:11427] *** End of error message ***
</pre>
{% endraw %}
