**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @107 : keyword ARG is compulsory for this action
[runnervmmtnos:33482] *** Process received signal ***
[runnervmmtnos:33482] Signal: Aborted (6)
[runnervmmtnos:33482] Signal code:  (-6)
[runnervmmtnos:33482] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd74b645330]
[runnervmmtnos:33482] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd74b69eb2c]
[runnervmmtnos:33482] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd74b64527e]
[runnervmmtnos:33482] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd74b6288ff]
[runnervmmtnos:33482] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd74baa5ff5]
[runnervmmtnos:33482] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd74babb0da]
[runnervmmtnos:33482] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd74baa5a55]
[runnervmmtnos:33482] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd74baa5a6f]
[runnervmmtnos:33482] [ 8] plumed_master(+0x146dd)[0x55fae87786dd]
[runnervmmtnos:33482] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd74b62a1ca]
[runnervmmtnos:33482] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd74b62a28b]
[runnervmmtnos:33482] [11] plumed_master(+0x15365)[0x55fae8779365]
[runnervmmtnos:33482] *** End of error message ***
</pre>
{% endraw %}
