<script>function amendment_arrow(input, amendment, amendmentVal, amendmentTextArray) {
  console.log(input)
  if (input === 'left') {
    if (amendmentVal > 0) {
      amendmentVal -= 1
      amendment.value = amendmentTextArray[amendmentVal]
      console.log('Expected amendment: ' + amendment)
      console.log('Expected amendment: ' + amendmentTextArray[amendmentVal])
    } else {
      console.log('Array length: ' + amendmentTextArray.length)
      console.log('Array iteration: ' + (amendmentVal + 1))
      console.log('Desired value out of range')
      console.log('Expected amendment: ' + amendment)
      console.log('Expected amendment: ' + amendmentTextArray[amendmentVal])
    }
  } else if (input === 'right') {
    if (amendmentVal < amendmentTextArray.length - 1) {
      amendmentVal += 1
      amendment.value = amendmentTextArray[amendmentVal]

      console.log('Expected amendment: ' + amendment)
      console.log('Expected amendment: ' + amendmentTextArray[amendmentVal])
    } else {
      console.log('Array length: ' + amendmentTextArray.length)
      console.log('Array iteration: ' + (amendmentVal + 1))
      console.log('Desired value out of range')
      console.log('Expected amendment: ' + amendment)
    }
  } else {
    amendment.value = 'An unexpected error has occured'
    console.log('An unexpected error has occured on Amendment 3')
    console.log('Array length: ' + amendmentTextArray.length)
    console.log('Array iteration: ' + (amendmentVal + 1))
    console.log('Expected amendment: ' + amendment)
  }
}


/* function s2_arrow(input) {
  console.log(input)
  if (input === 'left') {
    if (s2_val > 0) {
      s2_val -= 1
      s2.value = s2_array[s2_val]
      console.log('Expected amendment: ' + s2)
      console.log('Expected amendment: ' + s2_array[s2_val])
    } else {
      console.log('Array length: ' + s2_array.length)
      console.log('Array iteration: ' + (s2_val + 1))
      console.log('Desired value out of range')
      console.log('Expected amendment: ' + s2)
      console.log('Expected amendment: ' + s2_array[s2_val])
    }
  } else if (input === 'right') {
    if (s2_val < s2_array.length - 1) {
      s2_val += 1
      s2.value = s2_array[s2_val]

      console.log('Expected amendment: ' + s2)
      console.log('Expected amendment: ' + s2_array[s2_val])
    } else {
      console.log('Array length: ' + s2_array.length)
      console.log('Array iteration: ' + (s2_val + 1))
      console.log('Desired value out of range')
      console.log('Expected amendment: ' + s2)
    }
  } else {
    s2.value = 'An unexpected error has occured'
    console.log('An unexpected error has occured on Amendment 3')
    console.log('Array length: ' + s2_array.length)
    console.log('Array iteration: ' + (s2_val + 1))
    console.log('Expected amendment: ' + s2)
  }
} 
 function s3_arrow(input) {
  if (input === 'left') {
    if (s3_val > 0) {
      s3_val -= 1
      s3.value = s3_array[s3_val]
      console.log('Expected amendment: ' + s3)
      console.log('Expected amendment: ' + s3_array[s3_val])
    } else {
      console.log('Array length: ' + s3_array.length)
      console.log('Array iteration: ' + (s3_val + 1))
      console.log('Desired value out of range')
      console.log('Expected amendment: ' + s3)
    }
  } else if (input === 'right') {
    if (s3_val < s3_array.length - 1) {
      s3_val += 1
      s3.value = s3_array[s3_val]
      console.log('Expected amendment: ' + s3)
      console.log('Expected amendment: ' + s3_array[s3_val])
    } else {
      console.log('Array length: ' + s3_array.length)
      console.log('Array iteration: ' + (s3_val + 1))
      console.log('Desired value out of range')
      console.log('Expected amendment: ' + s3)
    }
  } else {
    s3.value = 'An unexpected error has occured'
    console.log('An unexpected error has occured on Amendment 3')
    console.log('Array length: ' + s3_array.length)
    console.log('Array iteration: ' + (s3_val + 1))

    console.log('Expected amendment: ' + s3)
  }
}

function s4_arrow(input) {
  if (input === 'left') {
    if (s4_val > 0) {
      s4_val -= 1
      s4.value = s4_array[s4_val]
      console.log('Expected amendment: ' + s4)
      console.log('Expected amendment: ' + s4_array[s4_val])
    } else {
      console.log('Array length: ' + s4_array.length)
      console.log('Array iteration: ' + (s4_val + 1))
      console.log('Desired value out of range')
      console.log('Expected amendment: ' + s4)
    }
  } else if (input === 'right') {
    if (s4_val < s4_array.length - 1) {
      s4_val += 1
      s4.value = s4_array[s4_val]
      console.log('Expected amendment: ' + s4)
      console.log('Expected amendment: ' + s4_array[s4_val])
    } else {
      console.log('Array length: ' + s4_array.length)
      console.log('Array iteration: ' + (s4_val + 1))
      console.log('Desired value out of range')
      console.log('Expected amendment: ' + s4)
    }
  } else {
    s4.value = 'An unexpected error has occured'
    console.log('An unexpected error has occured on Amendment 4')
    console.log('Array length: ' + s4_array.length)
    console.log('Array iteration: ' + (s4_val + 1))
    console.log('Expected amendment: ' + s4)
  }
}
 */</script>


