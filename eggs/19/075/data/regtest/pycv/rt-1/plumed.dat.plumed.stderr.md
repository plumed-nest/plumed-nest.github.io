**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: PYTHONCV LABEL=cv1 ATOMS=1,4 IMPORT=pycv FUNCTION=cv1
Maybe a missing space or a typo?
[fv-az985-228:69816] *** Process received signal ***
[fv-az985-228:69816] Signal: Aborted (6)
[fv-az985-228:69816] Signal code:  (-6)
[fv-az985-228:69816] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f139f242520]
[fv-az985-228:69816] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f139f2969fc]
[fv-az985-228:69816] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f139f242476]
[fv-az985-228:69816] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f139f2287f3]
[fv-az985-228:69816] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f139f6a4f26]
[fv-az985-228:69816] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f139f6b6d9c]
[fv-az985-228:69816] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f139f6b6e07]
[fv-az985-228:69816] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f139f6b70bb]
[fv-az985-228:69816] [ 8] plumed(+0x12f48)[0x564deca78f48]
[fv-az985-228:69816] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f139f229d90]
[fv-az985-228:69816] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f139f229e40]
[fv-az985-228:69816] [11] plumed(+0x131e5)[0x564deca791e5]
[fv-az985-228:69816] *** End of error message ***
</pre>
{% endraw %}
