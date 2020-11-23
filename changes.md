```
<AvField
	type={'text'}
	name={'first_name'}
	placeholder={'Your first name'}
	customLabel={({ ...props }) => <Label {...props}>First name*:</Label>}
	customGroup={({children, ...props}) => <InputGroup {...props}>{children}</InputGroup>}
	errorMessage={'Your first name is required.'}
	required
/>
```