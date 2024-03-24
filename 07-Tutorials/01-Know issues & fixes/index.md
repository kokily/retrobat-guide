# 알려진 문제 & 수정

이 섹션은 공식 지원 채널에서 사용자가 제기한 특정 문제에 대해 팀에서 제공하는 공식 수정 사항으로 지속적으로 업데이트됩니다.

## es_input 파일 정리

컨트롤러 설정이 엉망이 되어 새로 시작해야 하는 경우, 여기 `Retrobat\emulationstation\.emulationstation` 폴더에 복사할 수 있는 `es_input.cfg` 파일이 있습니다.

여기에는 표준 키보드 설정만 포함되어 있으므로 컨트롤러 구성을 다시 수행해야 합니다.

| es_input.cfg |
|:-:|
```xml
<?xml version="1.0"?>
<inputList>
	<inputConfig type="keyboard" deviceName="Keyboard" deviceGUID="-1">
		<input name="a" type="key" id="120" value="1" />
		<input name="b" type="key" id="122" value="1" />
		<input name="down" type="key" id="1073741905" value="1" />
		<input name="hotkey" type="key" id="1073742052" value="1" />
		<input name="l2" type="key" id="1073741898" value="1" />
		<input name="l3" type="key" id="1073741897" value="1" />
		<input name="left" type="key" id="1073741904" value="1" />
		<input name="pagedown" type="key" id="1073741902" value="1" />
		<input name="pageup" type="key" id="1073741899" value="1" />
		<input name="r2" type="key" id="1073741901" value="1" />
		<input name="r3" type="key" id="127" value="1" />
		<input name="right" type="key" id="1073741903" value="1" />
		<input name="select" type="key" id="8" value="1" />
		<input name="start" type="key" id="13" value="1" />
		<input name="up" type="key" id="1073741906" value="1" />
		<input name="x" type="key" id="113" value="1" />
		<input name="y" type="key" id="115" value="1" />
	</inputConfig>
</inputList>

```