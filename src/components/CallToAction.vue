<template>
  <section>
    <div class="container">
      <div class="call-to-action">
        <div class="row">
          <div class="col-sm-8 d-flex">
              <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="99" height="49" viewBox="0 0 99 49">
                <image id="_6a46b3eea1b8b9bb4cab9a0c26dc2a74-graduation-cap-icon-graduation-icons_copy_2" data-name="6a46b3eea1b8b9bb4cab9a0c26dc2a74-graduation-cap-icon-graduation-icons copy 2" width="99" height="49" xlink:href="data:img/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGMAAAAxCAYAAADOfRdpAAAF+UlEQVR4nO2cW2wUVRzGf1tqrVjEKiiVi8UWuWgLUgWhLaDFa9QEH4jGaHzz0agxxsujUUOiUV+ML5r44CUmvhg0gihghSKIFKpVkFZFEBRpoZWoXI45yTdx2MxMd5eZs5ful0xmup2dc/n+5389syljDEWG84FrgaXAHcC/wGqgC9gOHC22AXkoFjKmADcBy4BFwIyQ+/qBbuAzYD3wPXDCcV9zRqGSUQFcDywEbtH1+CyfcULEbAS+AHYAPyXU31hQSGRMBpYAHSLh6pifPyByNgFrga+BoZjbOCvkm4zrgFYRYM+1Dtvu14qx5HwFfOOw7UC4JuNi6fzbJf3zXTYegdNSY5aUdcBmYL/rTrgg4yqgTSroRmBS0g3GAOuRdeqwXto2YDjpRpMgY7xcz1tFQDNQHXcjjtEnt9l6aJ8De4F/4u5CXGRYV3Mx0C79Xx/HQwsUJ2VfNsje2FWzL46u5krGBcA84Gb5/k36bDTiMLAT+BJYA+zKNfDMhozLZXxt5LscaBylkz8S+rVqNsve7Mz0i1Fk2LTDHJ/025UwwcVoSgjWrnwrUj4FtgAHwoaXTsYl8vfblH5oGu2zGTMGpM42iSBLznGvCUvGncDdwCygAZhYKiMvAhyUZ2ZzaO9XAjUyvvVlIpzDxlyDMglj/WqqCpgtNWWTcwuKJEArJvwB9CoNYw18D/Cz1/8oAz5BccP9wAqlDCryOHDrQh7S+Zjcx7+AUzKUYyRQ5yrHdSFwKVCn63xg0Jdm2SI7kbEBD8ISuWp32fuB++TiTk1gcEZ69De5hN2SJI+EARGQKcYBF0n92v7OBVqkASYmEBsdlv7vlKHe5Zf8kZAJGSuB9xRn/KLPxmnVLBJZ9nxOjgP4URLTo2i2W4NKEim57QuUrJyvmkm2K39Yqfhtkv4u3xxljUzIuAd4RxK1PeSeKzUwLxXeEDGwg5rw1ZKgfi3ndFRJzVh3+wpgmlTOBKmhGglAlUqvJ7VqBnQclEro00o7oiMIKXmTzfIsbWp/esB99vs/SOo7Jfl9uU5+OuIiw49KxSmtChaXS4I+kLr7UIYsHY0KLGeI3GZN0NiYxtqvAOw7TWCvpDpI7VmCb5Mjc5mk3U7+Vj0nESRBhh8VWi17AkqeDVIPHVpV9Y6LS0Z92q2J3qDrQw77cAYqE37+aZU4PSxXdnepbE3S7UchJVU0XSsAqbNPZAPWSIicIZPJSJ1lZ2wt+yEVlua4HFwOsDbpQR0Dige868SRCRleR3Ldj/QqcIOLwcSMWrnzda7IyMSVm6ZzQ45tFM2+pQAMKah0gigyzgNeA17W328Dz+XQqdOuBlPsiFJTrysV4sHu7HhSKd9nR/vEJYGwldGSRoQfTykQKyNmhJERtpcVqa/JZSLiRxgZXRGGd7+CozJiRhgZNjJ9JuR/j2SZOS0jQ0QZ8FXA78BL8rltTudx4COHk2tzWL+qH0eUUBxW/eK4Vm9KtYwx2izn1TRqtKGuVgnHSYW+oWKkoO8t4Hld706YiL0ifIcSenukEof8RfsckFJZs0Y1jRlKSF6j7EDBVDNHIuMBX2cXS8rijEY3Kndl0w7bElJ/RqtpWGn1rYqZUEa2TRuxV8o5yR9s1jbieMP8j1PGmPYR7g86PjZn4oAx5hVjTIsxZkwOz0vqaDTGvGiMGfT19qgxZqarPkRF4OOU3PNQoR3l2cJLNB5T0GjVw8OqJThLNWQAW3F8TIWld3V7jYpWThBFRpNKrX5k+zaRNagzVSuw72O8kM96QYawtupe4AnNj7OYKspmdAR8li0Z1qt5WpJWbDmqVdpc4CRjywiVvvUqAvmxT2rmT1cdHE0IU1NTQl7xmlri717kFWFktMuAB2FW6U9LfhBGxrKI3swrlcEXGoLIqFaAF4ZCr2MXLYLImO3zmnoC9obOzXukWqIIIqNV50G9MJO+aatOsUMZMSOIjBU6P6pcTvqOPu93PcpImIxGpUDsr9K8qc+CNiEvLBMRP9KDvjrtKF/r+5GTRqmlv5UBrZbq6i2B8RcOgP8Ah/CgmimY6ocAAAAASUVORK5CYII="/>
              </svg>
              <div class="ms-3">
                <h2 class="text-white fw-bold">
                  Ultimate theme for online 
                  <span class="font-pristina fw-light">Courses</span> & <span class="font-pristina fw-light">Education</span>
                </h2>
                <p class="text-white">Your site can be built in less than you can expect!!</p>
              </div>
          </div>
          <div class="col-sm-4 text-right">
            <a href="#" class="btn btn-warning rounded-pill text-uppercase fw-bold">Buy this theme</a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'call-to-action'
}
</script>

<style lang="scss" scoped>
.call-to-action {
  background: linear-gradient(90deg, #4764fb 0%, #83acfd 100%);
  border-radius: 20px;
  padding: 50px 100px;

  p {
    font-family: Roboto;
    font-style: italic;
    letter-spacing: 1.2px;
  }
  h2 {
    font-size: 26px;
  }
  .btn {
    font-size: 15px;
    padding: 21px 50px;
  }
  .text-right {
    text-align: right;
  }
}
</style>