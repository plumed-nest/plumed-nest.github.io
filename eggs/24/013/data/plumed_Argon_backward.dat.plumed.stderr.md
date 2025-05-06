**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[fv-az807-718:61837] *** Process received signal ***
[fv-az807-718:61837] Signal: Aborted (6)
[fv-az807-718:61837] Signal code:  (-6)
[fv-az807-718:61837] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6fa5445330]
[fv-az807-718:61837] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6fa549eb2c]
[fv-az807-718:61837] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6fa544527e]
[fv-az807-718:61837] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6fa54288ff]
[fv-az807-718:61837] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6fa58a5ff5]
[fv-az807-718:61837] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6fa58bb0da]
[fv-az807-718:61837] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6fa58a5a55]
[fv-az807-718:61837] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6fa58a5a6f]
[fv-az807-718:61837] [ 8] plumed(+0x146dd)[0x55b5535cb6dd]
[fv-az807-718:61837] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6fa542a1ca]
[fv-az807-718:61837] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6fa542a28b]
[fv-az807-718:61837] [11] plumed(+0x15365)[0x55b5535cc365]
[fv-az807-718:61837] *** End of error message ***
</pre>
{% endraw %}
