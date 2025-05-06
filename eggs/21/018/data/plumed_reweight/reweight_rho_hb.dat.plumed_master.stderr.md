**Project ID:** [plumID:21.018]({{ '/' | absolute_url }}eggs/21/018/)  
Stderr for source:  plumed_reweight/reweight_rho_hb.dat   
Download: [zipped raw stdout](reweight_rho_hb.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_rho_hb.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[fv-az807-718:65395] *** Process received signal ***
[fv-az807-718:65395] Signal: Aborted (6)
[fv-az807-718:65395] Signal code:  (-6)
[fv-az807-718:65395] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1ec6a45330]
[fv-az807-718:65395] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1ec6a9eb2c]
[fv-az807-718:65395] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1ec6a4527e]
[fv-az807-718:65395] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1ec6a288ff]
[fv-az807-718:65395] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1ec6ea5ff5]
[fv-az807-718:65395] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1ec6ebb0da]
[fv-az807-718:65395] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1ec6ea5a55]
[fv-az807-718:65395] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1ec6ea5a6f]
[fv-az807-718:65395] [ 8] plumed_master(+0x146dd)[0x55e4863136dd]
[fv-az807-718:65395] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1ec6a2a1ca]
[fv-az807-718:65395] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1ec6a2a28b]
[fv-az807-718:65395] [11] plumed_master(+0x15365)[0x55e486314365]
[fv-az807-718:65395] *** End of error message ***
</pre>
{% endraw %}
