**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[runnervmkj6or:08602] *** Process received signal ***
[runnervmkj6or:08602] Signal: Aborted (6)
[runnervmkj6or:08602] Signal code:  (-6)
[runnervmkj6or:08602] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb971645330]
[runnervmkj6or:08602] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb97169eb2c]
[runnervmkj6or:08602] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb97164527e]
[runnervmkj6or:08602] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb9716288ff]
[runnervmkj6or:08602] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb971aa5ff5]
[runnervmkj6or:08602] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb971abb0da]
[runnervmkj6or:08602] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb971aa5a55]
[runnervmkj6or:08602] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb971aa5a6f]
[runnervmkj6or:08602] [ 8] plumed_master(+0x146dd)[0x5557871746dd]
[runnervmkj6or:08602] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb97162a1ca]
[runnervmkj6or:08602] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb97162a28b]
[runnervmkj6or:08602] [11] plumed_master(+0x15365)[0x555787175365]
[runnervmkj6or:08602] *** End of error message ***
</pre>
{% endraw %}
