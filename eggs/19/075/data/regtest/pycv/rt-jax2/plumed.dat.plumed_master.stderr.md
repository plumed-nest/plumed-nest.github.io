**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-jax2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:986) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&, const bool&)
ERROR
I cannot understand line: PYTHONCV LABEL=cv1 ATOMS=1,4,3 IMPORT=jaxcv FUNCTION=cv1
Maybe a missing space or a typo?
[fv-az985-228:70011] *** Process received signal ***
[fv-az985-228:70011] Signal: Aborted (6)
[fv-az985-228:70011] Signal code:  (-6)
[fv-az985-228:70011] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f5b36c42520]
[fv-az985-228:70011] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f5b36c969fc]
[fv-az985-228:70011] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f5b36c42476]
[fv-az985-228:70011] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f5b36c287f3]
[fv-az985-228:70011] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f5b370a4f26]
[fv-az985-228:70011] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f5b370b6d9c]
[fv-az985-228:70011] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f5b370b6e07]
[fv-az985-228:70011] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f5b370b70bb]
[fv-az985-228:70011] [ 8] plumed_master(+0x12e7f)[0x55bdc574ce7f]
[fv-az985-228:70011] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f5b36c29d90]
[fv-az985-228:70011] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f5b36c29e40]
[fv-az985-228:70011] [11] plumed_master(+0x13115)[0x55bdc574d115]
[fv-az985-228:70011] *** End of error message ***
</pre>
{% endraw %}
