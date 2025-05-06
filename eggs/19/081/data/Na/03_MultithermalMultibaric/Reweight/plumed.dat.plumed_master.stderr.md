**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @40 : keyword ARG is compulsory for this action
[fv-az807-718:68143] *** Process received signal ***
[fv-az807-718:68143] Signal: Aborted (6)
[fv-az807-718:68143] Signal code:  (-6)
[fv-az807-718:68143] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb994445330]
[fv-az807-718:68143] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb99449eb2c]
[fv-az807-718:68143] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb99444527e]
[fv-az807-718:68143] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb9944288ff]
[fv-az807-718:68143] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb9948a5ff5]
[fv-az807-718:68143] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb9948bb0da]
[fv-az807-718:68143] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb9948a5a55]
[fv-az807-718:68143] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb9948a5a6f]
[fv-az807-718:68143] [ 8] plumed_master(+0x146dd)[0x5602445836dd]
[fv-az807-718:68143] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb99442a1ca]
[fv-az807-718:68143] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb99442a28b]
[fv-az807-718:68143] [11] plumed_master(+0x15365)[0x560244584365]
[fv-az807-718:68143] *** End of error message ***
</pre>
{% endraw %}
