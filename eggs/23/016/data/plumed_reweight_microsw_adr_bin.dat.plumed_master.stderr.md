**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @173 : keyword ARG is compulsory for this action
[fv-az1911-722:06889] *** Process received signal ***
[fv-az1911-722:06889] Signal: Aborted (6)
[fv-az1911-722:06889] Signal code:  (-6)
[fv-az1911-722:06889] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbb6b845330]
[fv-az1911-722:06889] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbb6b89eb2c]
[fv-az1911-722:06889] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbb6b84527e]
[fv-az1911-722:06889] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbb6b8288ff]
[fv-az1911-722:06889] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbb6bca5ff5]
[fv-az1911-722:06889] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbb6bcbb0da]
[fv-az1911-722:06889] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbb6bca5a55]
[fv-az1911-722:06889] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbb6bca5a6f]
[fv-az1911-722:06889] [ 8] plumed_master(+0x146dd)[0x55d522cd86dd]
[fv-az1911-722:06889] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbb6b82a1ca]
[fv-az1911-722:06889] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbb6b82a28b]
[fv-az1911-722:06889] [11] plumed_master(+0x15365)[0x55d522cd9365]
[fv-az1911-722:06889] *** End of error message ***
</pre>
{% endraw %}
