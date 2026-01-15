**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s41 : missing SWITCH11 keyword
[runnervmmtnos:37730] *** Process received signal ***
[runnervmmtnos:37730] Signal: Aborted (6)
[runnervmmtnos:37730] Signal code:  (-6)
[runnervmmtnos:37730] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efdc9445330]
[runnervmmtnos:37730] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efdc949eb2c]
[runnervmmtnos:37730] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efdc944527e]
[runnervmmtnos:37730] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efdc94288ff]
[runnervmmtnos:37730] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efdc98a5ff5]
[runnervmmtnos:37730] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efdc98bb0da]
[runnervmmtnos:37730] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efdc98a5a55]
[runnervmmtnos:37730] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efdc98a5a6f]
[runnervmmtnos:37730] [ 8] plumed(+0x146dd)[0x55db9a1e16dd]
[runnervmmtnos:37730] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efdc942a1ca]
[runnervmmtnos:37730] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efdc942a28b]
[runnervmmtnos:37730] [11] plumed(+0x15365)[0x55db9a1e2365]
[runnervmmtnos:37730] *** End of error message ***
</pre>
{% endraw %}
