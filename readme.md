�}���R�t�A�� for EasyBotter
==========
ver.0.18 (2012-01-23; 2.04beta)  

<https://github.com/kww/markov4eb>  
<https://twitter.com/intent/user?user_id=51408776> (@wktk)


****


�d�l
----------
- bot ���猩���^�C�����C������A�ŐV 20 �� (?) �̃c�C�[�g���擾���ē��삵�܂��B
- �f�t�H���g�ł́A�c�C�[�g���̔��p # �� URL �͏�������܂��B
- ���� RT �ƁART ���� QT ���܂ރc�C�[�g�͘A���Ώۂ��珜����܂��B
- ���A�J�E���g�̃c�C�[�g���E���܂��B
- �ʏ�c�C�[�g�ł����v���C�����邱�Ƃ�����܂��B
- �}���R�t�A���ł̃��v���C���ݒ�ł��܂��B


****


�T���v��
----------
- ���̂܂ܐݒu������: [@e_markov](https://twitter.com/e_markov)  
- ������: [@k9_bot](https://twitter.com/k9_bot)


****



�g�p�菇
----------
1. __[EasyBotter](http://pha22.net/twitterbot/) �̐ݒu__


2. __�A�v���P�[�V���� ID �̎擾__

    - �uYahoo! JAPAN �f�x���b�p�[�l�b�g���[�N�v�̃A�v���P�[�V���� ID ���A
      <https://e.developer.yahoo.co.jp/webservices/register_application> ����擾���Ă��������B  
    - �擾�ɂ́AYahoo! JAPAN �Ƀ��O�C���ł��� ID ���K�v�ł��B  
    - �u�A�v���P�[�V�����̎�ށv�́u�F�؂�K�v�Ƃ��Ȃ�API���g�����A�v���P�[�V�����v�A�u�T�C�gURL�v�́uURL�Ȃ��v��I�����Ă��������B


3. __EasyBotter.php �̕ύX__

    - *EasyBotter.ph*p �� `class EasyBotter {` �̂������ɁA  
      *markov.php* �̒��g��S�ē\��t���Ă��������B


4. __bot.php �̕ύX__
    - *bot.php* (���O�ύX���Ă���ꍇ�͂������) �́A
      `$response = $eb->***( �` );` �̕��тɁA���̕���ǉ����Ă��������B

        - �ʏ�POST  
          `$response = $eb->markov( 'YJDN �̃A�v���P�[�V���� ID' );`

        - ���v���C  
          `$response = $eb->replymarkov( cron�Ԋu, 'YJDN �̃A�v���P�[�V���� ID' );`


5. __����ŏ��������ł��B__


****