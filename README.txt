coding: UTF-8

�}���R�t�A�� for EasyBotter
  �X�V:  0.18 (2012-01-23; 2.04beta)
  link:  https://github.com/kww/markov4eb
         https://twitter.com/intent/user?user_id=51408776 (@wktk)

 �d�l
    * bot ���猩���^�C�����C������A�ŐV 20 �� (?) �̃c�C�[�g���擾���ē��삵�܂��B
    * �f�t�H���g�ł́A�c�C�[�g���̔��p # �� URL �͏�������܂��B
    * ���� RT �ƁART ���� QT ���܂ރc�C�[�g�͘A���Ώۂ��珜����܂��B
    * ���A�J�E���g�̃c�C�[�g���E���܂��B
    * �ʏ�c�C�[�g�ł����v���C�����邱�Ƃ�����܂��B
    * �}���R�t�A���ł̃��v���C���ݒ�ł��܂��B

 �g�p�菇
    0. EasyBotter ��ݒu���Ă����Ă��������B

    1. �A�v���P�[�V���� ID �̎擾
         �uYahoo! JAPAN �f�x���b�p�[�l�b�g���[�N�v�̃A�v���P�[�V���� ID ���A���� URL ����擾���Ă��������B
         �`�ԑf��ׂ͂̈ɕK�v�ł��B�i�擾�ɂ́AYahoo! JAPAN �Ƀ��O�C���ł��� ID ���K�v�ł��B�j
           https://e.developer.yahoo.co.jp/webservices/register_application
         �u�A�v���P�[�V�����̎�ށv�́u�F�؂�K�v�Ƃ��Ȃ�API���g�����A�v���P�[�V�����v�A
         �u�T�C�gURL�v�́uURL�Ȃ��v��I�����Ă��������B

    2. EasyBotter.php �̕ύX
         EasyBotter.php �� �uclass EasyBotter { �v�̂������ɁAmarkov.php �̒��g��S�ē\��t���Ă��������B

    3. bot.php �̕ύX
         bot.php (���O�ύX���Ă���ꍇ�͂������) �́A
         $response = $eb->***( �` ); �̕��тɁA���̕���ǉ����Ă��������B
           �ʏ�POST
             $response = $eb->markov( 'YJDN �̃A�v���P�[�V���� ID' );
           ���v���C
             $response = $eb->replymarkov( cron�Ԋu, 'YJDN �̃A�v���P�[�V���� ID' );

    4. ����ŏ��������ł��B

