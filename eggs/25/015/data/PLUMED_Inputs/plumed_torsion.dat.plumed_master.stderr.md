**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_torsion.dat   
Download: [zipped raw stdout](plumed_torsion.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_torsion.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPATOMS with label @6 : it was not possible to interpret atom name t1_grp
[pkrvmxyh4eaekms:05668] *** Process received signal ***
[pkrvmxyh4eaekms:05668] Signal: Aborted (6)
[pkrvmxyh4eaekms:05668] Signal code:  (-6)
[pkrvmxyh4eaekms:05668] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0ded845330]
[pkrvmxyh4eaekms:05668] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0ded89eb2c]
[pkrvmxyh4eaekms:05668] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0ded84527e]
[pkrvmxyh4eaekms:05668] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0ded8288ff]
[pkrvmxyh4eaekms:05668] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0dedca5ff5]
[pkrvmxyh4eaekms:05668] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0dedcbb0da]
[pkrvmxyh4eaekms:05668] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0dedca5a55]
[pkrvmxyh4eaekms:05668] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0dedca5a6f]
[pkrvmxyh4eaekms:05668] [ 8] plumed_master(+0x146dd)[0x55dce61606dd]
[pkrvmxyh4eaekms:05668] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0ded82a1ca]
[pkrvmxyh4eaekms:05668] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0ded82a28b]
[pkrvmxyh4eaekms:05668] [11] plumed_master(+0x15365)[0x55dce6161365]
[pkrvmxyh4eaekms:05668] *** End of error message ***
</pre>
{% endraw %}
