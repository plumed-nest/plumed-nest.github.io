**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[fv-az807-718:61888] *** Process received signal ***
[fv-az807-718:61888] Signal: Aborted (6)
[fv-az807-718:61888] Signal code:  (-6)
[fv-az807-718:61888] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f14a9245330]
[fv-az807-718:61888] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f14a929eb2c]
[fv-az807-718:61888] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f14a924527e]
[fv-az807-718:61888] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f14a92288ff]
[fv-az807-718:61888] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f14a96a5ff5]
[fv-az807-718:61888] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f14a96bb0da]
[fv-az807-718:61888] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f14a96a5a55]
[fv-az807-718:61888] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f14a96a5a6f]
[fv-az807-718:61888] [ 8] plumed(+0x146dd)[0x55fceda536dd]
[fv-az807-718:61888] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f14a922a1ca]
[fv-az807-718:61888] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f14a922a28b]
[fv-az807-718:61888] [11] plumed(+0x15365)[0x55fceda54365]
[fv-az807-718:61888] *** End of error message ***
</pre>
{% endraw %}
