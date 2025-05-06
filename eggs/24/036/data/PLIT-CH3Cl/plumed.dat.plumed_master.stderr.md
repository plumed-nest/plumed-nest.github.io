**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-CH3Cl/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[fv-az807-718:61416] *** Process received signal ***
[fv-az807-718:61416] Signal: Aborted (6)
[fv-az807-718:61416] Signal code:  (-6)
[fv-az807-718:61416] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3e3ac45330]
[fv-az807-718:61416] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3e3ac9eb2c]
[fv-az807-718:61416] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3e3ac4527e]
[fv-az807-718:61416] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3e3ac288ff]
[fv-az807-718:61416] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3e3b0a5ff5]
[fv-az807-718:61416] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3e3b0bb0da]
[fv-az807-718:61416] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3e3b0a5a55]
[fv-az807-718:61416] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3e3b0a5a6f]
[fv-az807-718:61416] [ 8] plumed_master(+0x146dd)[0x556510a476dd]
[fv-az807-718:61416] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3e3ac2a1ca]
[fv-az807-718:61416] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3e3ac2a28b]
[fv-az807-718:61416] [11] plumed_master(+0x15365)[0x556510a48365]
[fv-az807-718:61416] *** End of error message ***
</pre>
{% endraw %}
