# YAME: A MIPS Editor
YAME ��һ���򵥵� MIPS �༭�� / ����� / ������� / ģ������������ͼ�ν��档������Ϊ�㽭��ѧ���������ɡ��γ̣���ʦ��LXQ����д�Ŀγ���Ŀ��

YAME �� YAME: A MIPS Editor ����д��Ҳ������Ϊ�� Yet Another MIPS Editor ����д��

## Ԥ��
![assemble](screenshot/assemble.png)

![pseudo](screenshot/pseudo.png)

![simulate](screenshot/simulate.png)

## ����
- ֧���﷨������
- ֧���Զ���αָ�
- ֧�� .asm ����ļ����Ϊ .coe �ļ��� .bin �ļ���
- ֧�� .coe �ļ��� .bin �ļ������Ϊ .asm ����ļ����Ϊ��
- ֧��ģ�����У�֧��ģ���ն����������
- ֧�ּ򵥵ĵ��Թ��ܣ��������С�ȫ�����С��鿴�Ĵ������ڴ��ֵ����

## ָ�
YAME ֧������ָ��Ļ�ࡢ�������ģ�⡣

֧�ֵ� R ָ���У�
- add
- addu
- and
- div
- divu
- jalr
- jr
- mfhi
- mflo
- mthi
- mtlo
- mult
- multu
- nor
- or
- sll
- sllv
- slt
- sltu
- sra
- srav
- srl
- srlv
- sub
- subu
- syscall�����֣�
- xor

֧�ֵ� I ָ���У�
- addi
- addiu
- andi
- beq
- bgez
- bgezal
- bgtz
- blez
- bltz
- bltzal
- bne
- lb
- lbu
- lh
- lhu
- lui
- lw
- ori
- sb
- slti
- sltiu
- sh
- sw
- xori

֧�ֵ� J ָ���У�
- j
- jal

֧�ֵĸ�ʽָ���У�
- .text
- .data
- .2byte
- .4byte
- .8byte
- .ascii
- .asciiz
- .byte
- .dword
- .half
- .space
- .word

֧�ֵ� syscall �����У�
- 1�����������
- 4������ַ�����
- 5������������
- 8�������ַ�����
- 10���˳���
- 11������ַ���
- 12�������ַ���
- 30������ϵͳʱ�䣩
- 41�����������
- 42���з�Χ�����������

## αָ��
YAME ���������Ƕ��Զ���αָ���֧�֡��򿪡����� - αָ����ڣ�������ӡ�ɾ�����޸�αָ�

�û��ṩαָ�������������������Ӧ����ָ���YAME ���ڻ��ʱ��αָ��ת��Ϊ��Ӧ��ָ�

�ڡ���ָ������У��������� `[x]` ��ʾ�� x ������������ `@` ��Χ�ı�ǩ������ñ�ǩ�ĵ�ַ�����磬`@[2]@` ��ʾ�� 2 ���������ĵ�ַ��Ҫ��� 2 �������������Ǳ�ǩ����

YAME �������ļ��У��Ѿ���д����һЩαָ����Դ�αָ��ڽ��в鿴���޸ġ�

## ģ��
YAME ���м򵥵�ģ������Թ��ܡ���ģ�⡱������һ���򵥵�ģ���նˣ�����ͨ�� syscall ָ�����ն������Ϣ������ն˶����û�������Ϣ���ն������Ϣ�ð�ɫ�ֱ�ʾ���û�������Ϣ����ɫ�ֱ�ʾ��

����ʹ�� test �ļ����е� guess.asm �ļ���һ����������Ϸ��[ԭ github ��ַ���](https://github.com/plazagonzalezd/MIPS-Game)��guess.asm �ļ���ԭ�ļ����������޸ģ����� YAME �Ļ����ģ�⹦�ܡ�