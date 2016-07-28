# phone
// this line loads the library  require('/path/to/twilio-php/Services/Twilio.php');    $account_sid = 'ACdbe518f4059ddcae8465e98d2535de79';  $auth_token = '977f16d7149515d754d8c6008a5251fa';  $client = new Services_Twilio($account_sid, $auth_token);    $caller = $client->account->outgoing_caller_ids->get('PN73032c01320b08872905fe2d87fdec6c');  $caller->update(array());
