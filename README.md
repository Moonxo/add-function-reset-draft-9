# add-function-reset-draft-9
function resetMyGarage() external override {
        delete garages[msg.sender];
    }
