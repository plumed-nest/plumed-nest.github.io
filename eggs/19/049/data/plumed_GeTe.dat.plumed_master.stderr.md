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
[runnervmvrwv9:10134] *** Process received signal ***
[runnervmvrwv9:10134] Signal: Aborted (6)
[runnervmvrwv9:10134] Signal code:  (-6)
[runnervmvrwv9:10134] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff2d7e45330]
[runnervmvrwv9:10134] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff2d7e9eb2c]
[runnervmvrwv9:10134] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff2d7e4527e]
[runnervmvrwv9:10134] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff2d7e288ff]
[runnervmvrwv9:10134] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff2d82a5ff5]
[runnervmvrwv9:10134] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff2d82bb0da]
[runnervmvrwv9:10134] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff2d82a5a55]
[runnervmvrwv9:10134] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff2d82a5a6f]
[runnervmvrwv9:10134] [ 8] plumed_master(+0x146dd)[0x558df42956dd]
[runnervmvrwv9:10134] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff2d7e2a1ca]
[runnervmvrwv9:10134] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff2d7e2a28b]
[runnervmvrwv9:10134] [11] plumed_master(+0x15365)[0x558df4296365]
[runnervmvrwv9:10134] *** End of error message ***
</pre>
{% endraw %}
