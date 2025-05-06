**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[fv-az807-718:67934] *** Process received signal ***
[fv-az807-718:67934] Signal: Aborted (6)
[fv-az807-718:67934] Signal code:  (-6)
[fv-az807-718:67934] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5f60845330]
[fv-az807-718:67934] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5f6089eb2c]
[fv-az807-718:67934] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5f6084527e]
[fv-az807-718:67934] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5f608288ff]
[fv-az807-718:67934] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5f60ca5ff5]
[fv-az807-718:67934] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5f60cbb0da]
[fv-az807-718:67934] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5f60ca5a55]
[fv-az807-718:67934] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5f60ca5a6f]
[fv-az807-718:67934] [ 8] plumed_master(+0x146dd)[0x55a2d99426dd]
[fv-az807-718:67934] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5f6082a1ca]
[fv-az807-718:67934] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5f6082a28b]
[fv-az807-718:67934] [11] plumed_master(+0x15365)[0x55a2d9943365]
[fv-az807-718:67934] *** End of error message ***
</pre>
{% endraw %}
