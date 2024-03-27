**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:302) void PLMD::Action::error(const string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[fv-az985-228:69399] *** Process received signal ***
[fv-az985-228:69399] Signal: Aborted (6)
[fv-az985-228:69399] Signal code:  (-6)
[fv-az985-228:69399] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fc522242520]
[fv-az985-228:69399] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fc5222969fc]
[fv-az985-228:69399] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fc522242476]
[fv-az985-228:69399] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fc5222287f3]
[fv-az985-228:69399] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fc5226a4f26]
[fv-az985-228:69399] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fc5226b6d9c]
[fv-az985-228:69399] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fc5226b6e07]
[fv-az985-228:69399] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fc5226b70bb]
[fv-az985-228:69399] [ 8] plumed_master(+0x12e7f)[0x55fea6010e7f]
[fv-az985-228:69399] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fc522229d90]
[fv-az985-228:69399] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fc522229e40]
[fv-az985-228:69399] [11] plumed_master(+0x13115)[0x55fea6011115]
[fv-az985-228:69399] *** End of error message ***
</pre>
{% endraw %}
