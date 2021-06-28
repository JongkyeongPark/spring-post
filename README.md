# spring-post

## description

CRUD 중 C에 해당하는 기능을 한다. 
json을 통해 데이터를 주고받으며, 다음과 같은 양식을 사용한다. 
{
  "account" : "user01",
  "email" : "jk@gmail.com",
  "address" : "공부",
  "password" : "1234",
  "phone_number" : "010-1111-1111",
  "OTP" : "12345"
}

## annotaion

@RestController : Rest API 설정
@RequestMaping : 리소스를 설정한다
@PostMapping : Post Resouce를 설정한다
@RequestBody : Request Body 부분으 Parsing한다
@PathVariable : URL Path Variable Parsing
@JsonProperty : json naming
@JsonNaming : class json naming
