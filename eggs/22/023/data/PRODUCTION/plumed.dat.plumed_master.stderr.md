**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../structure.pdb
[fv-az985-228:69006] *** Process received signal ***
[fv-az985-228:69006] Signal: Aborted (6)
[fv-az985-228:69006] Signal code:  (-6)
[fv-az985-228:69006] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7c69c42520]
[fv-az985-228:69006] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f7c69c969fc]
[fv-az985-228:69006] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7c69c42476]
[fv-az985-228:69006] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f7c69c287f3]
[fv-az985-228:69006] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f7c6a0a4f26]
[fv-az985-228:69006] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f7c6a0b6d9c]
[fv-az985-228:69006] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f7c6a0b6e07]
[fv-az985-228:69006] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f7c6a0b70bb]
[fv-az985-228:69006] [ 8] plumed_master(+0x12e7f)[0x56363abe9e7f]
[fv-az985-228:69006] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7c69c29d90]
[fv-az985-228:69006] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7c69c29e40]
[fv-az985-228:69006] [11] plumed_master(+0x13115)[0x56363abea115]
[fv-az985-228:69006] *** End of error message ***
</pre>
{% endraw %}
