# everyday_oil_price

import requests 
api_code = 'F739200410'
r2 = requests.get(f'http://www.opinet.co.kr/api/lowTop10.do?out=xml&code={api_code}&prodcd=B027&area=01')
r2.text
