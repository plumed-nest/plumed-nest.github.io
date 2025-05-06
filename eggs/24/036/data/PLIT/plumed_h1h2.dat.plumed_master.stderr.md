**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT/plumed_h1h2.dat   
Download: [zipped raw stdout](plumed_h1h2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_h1h2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @49 : keyword ARG is compulsory for this action
[fv-az807-718:61350] *** Process received signal ***
[fv-az807-718:61350] Signal: Aborted (6)
[fv-az807-718:61350] Signal code:  (-6)
[fv-az807-718:61350] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5503645330]
[fv-az807-718:61350] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f550369eb2c]
[fv-az807-718:61350] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f550364527e]
[fv-az807-718:61350] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f55036288ff]
[fv-az807-718:61350] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5503aa5ff5]
[fv-az807-718:61350] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5503abb0da]
[fv-az807-718:61350] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5503aa5a55]
[fv-az807-718:61350] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5503aa5a6f]
[fv-az807-718:61350] [ 8] plumed_master(+0x146dd)[0x55e89cda76dd]
[fv-az807-718:61350] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f550362a1ca]
[fv-az807-718:61350] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f550362a28b]
[fv-az807-718:61350] [11] plumed_master(+0x15365)[0x55e89cda8365]
[fv-az807-718:61350] *** End of error message ***
</pre>
{% endraw %}
