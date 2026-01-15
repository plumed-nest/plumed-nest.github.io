**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[runnervmmtnos:37638] *** Process received signal ***
[runnervmmtnos:37638] Signal: Aborted (6)
[runnervmmtnos:37638] Signal code:  (-6)
[runnervmmtnos:37638] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd6ace45330]
[runnervmmtnos:37638] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd6ace9eb2c]
[runnervmmtnos:37638] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd6ace4527e]
[runnervmmtnos:37638] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd6ace288ff]
[runnervmmtnos:37638] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd6ad2a5ff5]
[runnervmmtnos:37638] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd6ad2bb0da]
[runnervmmtnos:37638] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd6ad2a5a55]
[runnervmmtnos:37638] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd6ad2a5a6f]
[runnervmmtnos:37638] [ 8] plumed(+0x146dd)[0x55eb6e2946dd]
[runnervmmtnos:37638] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd6ace2a1ca]
[runnervmmtnos:37638] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd6ace2a28b]
[runnervmmtnos:37638] [11] plumed(+0x15365)[0x55eb6e295365]
[runnervmmtnos:37638] *** End of error message ***
</pre>
{% endraw %}
