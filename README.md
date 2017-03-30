# Yii2 Events list for Behaviors

<h2>MVC</h2>
<p><strong>Controller или Module (yii\base\Controller or yii\base\Module)</strong><br>
EVENT_BEFORE_ACTION<br>
EVENT_AFTER_ACTION</p>
<p><strong>Model (yii\base\Model)</strong><br>
EVENT_BEFORE_VALIDATE<br>
EVENT_AFTER_VALIDATE</p>
<p><strong>View (yii\base\View)</strong><br>
EVENT_BEGIN_PAGE<br>
EVENT_END_PAGE<br>
EVENT_BEFORE_RENDER<br>
EVENT_AFTER_RENDER</p>
<p><strong>View, that is inherited from the view (yii\web\View)</strong><br>
EVENT_BEGIN_BODY<br>
EVENT_END_BODY</p>
<h2>Database Events</h2>
<p><strong>ActiveRecord (yii\db\BaseActiveRecord)</strong><br>
EVENT_INIT<br>
EVENT_AFTER_FIND<br>
EVENT_BEFORE_INSERT<br>
EVENT_AFTER_INSERT<br>
EVENT_BEFORE_UPDATE<br>
EVENT_AFTER_UPDATE<br>
EVENT_BEFORE_DELETE<br>
EVENT_AFTER_DELETE</p>
<p><strong>ActiveQuery (yii\db\ActiveQuery)</strong><br>
EVENT_INIT</p>
<p><strong>Connection (yii\db\Connection)</strong><br>
EVENT_AFTER_OPEN<br>
EVENT_BEGIN_TRANSACTION<br>
EVENT_COMMIT_TRANSACTION<br>
EVENT_ROLLBACK_TRANSACTION</p>
<h2>Query Events</h2>
<p><strong>Application (yii\base\Application)</strong><br>
EVENT_BEFORE_REQUEST<br>
EVENT_AFTER_REQUEST</p>
<p><strong>Response (yii\web\Response)</strong><br>
EVENT_BEFORE_SEND<br>
EVENT_AFTER_SEND<br>
EVENT_AFTER_PREPARE</p>
<h2>Components Events</h2>
<p><strong>MessageSource (yii\i18n\MessageSource)</strong><br>
EVENT_MISSING_TRANSLATION</p>
<p><strong>BaseMailer (yii\mail\BaseMailer)</strong><br>
EVENT_BEFORE_SEND<br>
EVENT_AFTER_SEND</p>
<p><strong>User (yii\web\User)</strong><br>
EVENT_BEFORE_LOGIN<br>
EVENT_AFTER_LOGIN<br>
EVENT_BEFORE_LOGOUT<br>
EVENT_AFTER_LOGOUT</p>

