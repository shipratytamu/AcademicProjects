

describe("Includes validations for index page", function () {
    var indexPage;

    beforeEach(function () {
        indexPage = window.indexPage.validationFunctions;
    });

    it("Check for list data", function () {
        // We are going to pass "" (null) value to the function 
        var retVal = indexPage.getListData();
        expect(retVal).toBeTruthy();
    });

});