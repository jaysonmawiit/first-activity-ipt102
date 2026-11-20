# first-activity-ipt102
<?php // hello.php - returns data as JSON, not HTML
header('Content-Type: application/json');

$response = [
    'message' => 'Hello from the server!',
    'student' => 'Jayson mawiit',
    'course' => 'IPT 2',
    'time' => date('Y-m-d H:i:s')
];

echo json_encode($response);
