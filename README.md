# StringBuilderTemporary

C#�ł́Astring���m�̑����Z���� temporary�Ń��������ʂɊm�ۂ���邽�߁ASystem.Text.StringBuffer�̎g�p��������p�t�H�[�}���X�I�ɂ��������I�ɂ��ǂ��ł��B

�ł����A���ɏo���オ���Ă��܂������̂��C�`�C�`�Ή�����̂͂ƂĂ���ςł��B
�����ŁA�������܂Ƃ��ɂ���R�[�h���ȒP�ɏ����邽�߂̃N���X������p�ӂ��܂���


string str = "aaa" + 20 + "bbbb"; <br />
�@�@��<br/>
string str = Sbt.i + "aaa" + 20 + "bbbb"; <br/>
�Ƃ��邱�ƂŁA�������啪�܂Ƃ��ɂȂ�܂��B

Sbt.i�́AThreadSafe�ł͂���܂���B���Ɠ����I�u�W�F�N�g���g���܂킵�܂��B
���������P�[�X�Ŏg�������ꍇ�́ASbt.Create()�����Ɏg�p���Ă�������

# String�ł̉��Z�����̏d���e�X�g
�{�v���W�F�N�g�ɂ́AString�ł̉��Z�������h�������d�����m�F���邽�߂Ƀe�X�g�P�[�X��p�ӂ��܂����B
test�V�[�����J���Ď��s���Ă݂Ă��������BProfiler�Ŋm�F����ƃh���قǏd�������m�F�ł��܂��B

��ʂ��N���b�N���邱�ƂŁA����� Sbt.i�����邩�ǂ����̕ύX���\�ɂȂ��Ă��܂��B
��ʒ��́usbt Flag�v��true�ɂȂ邱�Ƃŏ������i�i�Ɍy���Ȃ�̂��m�F�ł��邩�Ǝv���܂��B


