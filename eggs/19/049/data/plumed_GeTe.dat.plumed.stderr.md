**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[runnervmmklqx:11410] *** Process received signal ***
[runnervmmklqx:11410] Signal: Aborted (6)
[runnervmmklqx:11410] Signal code:  (-6)
[runnervmmklqx:11410] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f044bc45330]
[runnervmmklqx:11410] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f044bc9eb2c]
[runnervmmklqx:11410] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f044bc4527e]
[runnervmmklqx:11410] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f044bc288ff]
[runnervmmklqx:11410] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f044c0a5ff5]
[runnervmmklqx:11410] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f044c0bb0da]
[runnervmmklqx:11410] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f044c0a5a55]
[runnervmmklqx:11410] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f044c0a5a6f]
[runnervmmklqx:11410] [ 8] plumed(+0x146dd)[0x55b61e1d56dd]
[runnervmmklqx:11410] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f044bc2a1ca]
[runnervmmklqx:11410] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f044bc2a28b]
[runnervmmklqx:11410] [11] plumed(+0x15365)[0x55b61e1d6365]
[runnervmmklqx:11410] *** End of error message ***
</pre>
{% endraw %}
