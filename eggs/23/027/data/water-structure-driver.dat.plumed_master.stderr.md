**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  water-structure-driver.dat   
Download: [zipped raw stdout](water-structure-driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](water-structure-driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @173 : keyword ARG is compulsory for this action
[fv-az789-879:61065] *** Process received signal ***
[fv-az789-879:61065] Signal: Aborted (6)
[fv-az789-879:61065] Signal code:  (-6)
[fv-az789-879:61065] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9370045330]
[fv-az789-879:61065] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f937009eb2c]
[fv-az789-879:61065] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f937004527e]
[fv-az789-879:61065] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f93700288ff]
[fv-az789-879:61065] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f93704a5ff5]
[fv-az789-879:61065] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f93704bb0da]
[fv-az789-879:61065] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f93704a5a55]
[fv-az789-879:61065] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f93704a5a6f]
[fv-az789-879:61065] [ 8] plumed_master(+0x146dd)[0x559df25b36dd]
[fv-az789-879:61065] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f937002a1ca]
[fv-az789-879:61065] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f937002a28b]
[fv-az789-879:61065] [11] plumed_master(+0x15365)[0x559df25b4365]
[fv-az789-879:61065] *** End of error message ***
</pre>
{% endraw %}
